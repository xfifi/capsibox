Température des règles aluminium maçon (rampe leds) :
- sonde epcos 100k + pate thermique (attention générer une table de valeurs)
- pwm des ventilos 12v

Mesure température / humidité de la poupo :
- BME280 en i2c

Mesure température environnement :
- DS1820 and co

RTC sauvegardé :
- DS3231 / DS1307

Gestion de l'eau bac de culture (en cas de petite absence) :
- pompe
- niveau d'eau bac
- niveau réserve

Gestion cable chauffant
- relai

Mesure éventuelle de certains godets :
- sonde capacitive humidité godet (en wireless)

Affichage + interactions :
- écran TFT 2.8" tactile spi 
  - Que doit-on afficher ? :
    - phase lunaire (pour ceux qui jardine avec la lune)
    - température + humidité intérieure
    - température environnement
    - date + heure
    - indications des éclairage
    - indication de la ventilation
    - indication cable chauffant
    - niveau éventuel eau bac de culture + réserve
    - ...
    

Geekerie :
- serveur http pour gestion depuis un navigateur
- wifi
- communication bluetooth avec sondes wireless
- relevé simple météo locale

Gestion éclairage des leds DOB4075 20W (photopériode)
- relais

Protection :
- dijoncteur diff 30mA
