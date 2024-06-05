# esphome_hisense_ac
Support for some Hisense AC via ESPHome

This integration can control the AC instead of getting current status of AC, I am still working for it.
Only tested on my Hisense AC, not all Hisense AC works.

* https://community.home-assistant.io/t/working-on-integration-for-hisense-aeh-w4a1-module/146243
* https://github.com/deiger/AirCon/
* https://github.com/simoneluconi/hisense-aeh-w4a1
* https://github.com/pslawinski/esphome_airconintl

I'm using an ESP-8266 NodeMCU directly connected to the AC connector.

The pinout of the connector is:
1) VCC
2) RX
3) TX
4) GND
