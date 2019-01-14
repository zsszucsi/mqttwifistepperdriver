# mqttwifistepperdriver
A NodeRED-MQTT-WiFi stepper motor driver with ESP8266

Software modules: 
  MQTT communication is using pubsubclient by knolleary https://github.com/knolleary/pubsubclient 
  New WiFi network can be set up using WiFiManager by tzapu https://github.com/tzapu/WiFiManager  
For the stepper logic consider the below links:  
  Microstepping: https://github.com/arduino-libraries/Stepper/pull/5/files 
  SimpleStepper: https://github.com/megablue/SimpleStepper 
Later plans for software:
  MQTT secure connection: https://internetofhomethings.com/homethings/?p=1820

Hardware: 
  The core of the application is the ESP8266-12F microcontroller with WiFi, motor driver is done by the ULN2003.
  Panel is designed in Eagle, you may find it in the repo, built at jlcpcb, Hongkong for 2$
  
  
