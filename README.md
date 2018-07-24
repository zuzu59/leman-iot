# leman-iot
Communauté Lémanique d'IoT basé sur le module NodeMCU ESP8266 Lua ;-)

<p align="center">
  <img src="https://raw.githubusercontent.com/zuzu59/leman-iot/master/NodeMCU.png">
</p>

## Buts
Ce petit module à seulement 2$ est juste incroyable, il se programme hyper facilement en Lua et c'est vraiment trop dommage de ne pas le connaître.

C'est pourquoi j'ai créé cette communauté d'utilisateurs afin de pouvoir tous nous réunir et partager nos expériences sur le sujet !

## Slack pour cette communauté
[https://join.slack.com/t/leman-iot/shared_invite/enQtNDA0MTY0NzI2MTMzLTNmNGQ3YTA3NGMwNzgxMTY3NjJkNjNmMzYyNzU4YWNkOWQyNTA5MWM0ZjE5MWM2YWUxZWMzMjI2YThlN2UxZDY](https://join.slack.com/t/leman-iot/shared_invite/enQtNDA0MTY0NzI2MTMzLTNmNGQ3YTA3NGMwNzgxMTY3NjJkNjNmMzYyNzU4YWNkOWQyNTA5MWM0ZjE5MWM2YWUxZWMzMjI2YThlN2UxZDY)

## ESP8266
L’ESP8266 est un circuit intégré à microcontrôleur avec stack TCPIP WiFi développé par le fabricant chinois Espressif.

En août 2014, les passionnés d’électronique commencent à s’intéresser à la version ESP-01 de ce circuit intégré produite par une entreprise tierce, AI-Thinker. Celui-ci, de taille réduite, permet de connecter un microcontrôleur à un réseau WiFi et d’établir des connexions TCP/IP avec des commandes Hayes. La traduction progressive de la documentation (à l'origine uniquement en chinois) motivée par le bas prix du circuit a permis le développement d'une communauté de développeurs et de passionnés de l'ESP8266.

Fin octobre 2014, Espressif propose un kit de développement logiciel (SDK) permettant de programmer le circuit sans recourir à l’utilisation d’un microcontrôleur additionnel. Depuis, Espressif a sorti quantité de nouvelles versions du SDK et ce sous deux variantes : une basée sur RTOS et une autre basée sur les fonctions de rappel (callbacks).

(Source Wikipedia)
[https://fr.wikipedia.org/wiki/ESP8266](https://fr.wikipedia.org/wiki/ESP8266)

Une des dernières versions ESP8266 est juste merveilleuse:

* 32-bit RISC CPU: Tensilica Xtensa LX106, 80 MHz
* 64 KiB of instruction RAM, 96 KiB of data RAM
* External QSPI flash - 512 KiB to 32 Mib (attention c'est des bits !)
* IEEE 802.11 b/g/n Wi-Fi
* Integrated TR switch, balun, LNA, power amplifier and matching network
* WEP or WPA/WPA2 authentication, or open networks
* 16 GPIO pins
* SPI, I²C,
* I²S interfaces with DMA (sharing pins with GPIO)
* UART on dedicated pins, plus a transmit-only UART can be enabled on GPIO2
* 1 10-bit ADC

## NodeMCU ESP8266 Lua
Les déclinaisons en module NodeMCU sont très utilisées dans la plate-forme open source IoT, en particulier avec le firmware Lua, qui permet de programmer en langage haut niveau.

Mais si on veut pouvoir utiliser toute la puissance de la bête, on utilise l'environnement de développement IDE d'ARDUINO et on programme en C++

[https://fr.wikipedia.org/wiki/NodeMCU](https://fr.wikipedia.org/wiki/NodeMCU)

Et ce module coûte juste 2$ en Chine:

[https://www.aliexpress.com/item/1pcs-V3-NodeMcu-Lua-WIFI-module-integration-of-ESP8266-extra-memory-32M-Flash-USB-serial-CH340G/32879758161.html](https://www.aliexpress.com/item/1pcs-V3-NodeMcu-Lua-WIFI-module-integration-of-ESP8266-extra-memory-32M-Flash-USB-serial-CH340G/32879758161.html)

Donc, pour seulement 2$ on a un MCPU avec une connexion WIFI et pleins de mémoire pour le programme, et je ne parle pas de la consommation au repos. Cela vaut donc vraiment la peine de s'y pencher une fois dessus ;-)

## Documentation
Superbe documentation, à lire avant toute chose, qui résume bien la saga ESP8266

[https://projetsdiy.fr/esp8266-guide-de-choix-achat-projets-diy/](https://projetsdiy.fr/esp8266-guide-de-choix-achat-projets-diy/)

## Data sheet
Data sheet ESP8266EX

[https://www.espressif.com/sites/default/files/documentation/0a-esp8266ex_datasheet_en.pdf](https://www.espressif.com/sites/default/files/documentation/0a-esp8266ex_datasheet_en.pdf)

## Ma petite documentation perso
Ma petite documentation pense bête où je mets pour l'instant pleins de choses que j'ai trouvées ce NodeMCU ESP8266 Lua

[https://docs.google.com/document/d/1q64uK3IMOgEDdKaIAttbYuFt4GuLQ06k3FLeyfCsWLg/edit?usp=sharing](https://docs.google.com/document/d/1q64uK3IMOgEDdKaIAttbYuFt4GuLQ06k3FLeyfCsWLg/edit?usp=sharing)


## Mon dépôt fourre-tout
Mon dépôt où je mets pour l'instant pleins de choses sur ce NodeMCU ESP8266 Lua

[https://github.com/zuzu59/NodeMCU_Lua](https://github.com/zuzu59/NodeMCU_Lua)

zf180724.1624

