# simplewater
Simple watering system, arduino keeping my plants alive.

This arduino sketch will be for an arduino nano, that will control a small fountain pump with a mosfet.
Watering will be triggered with a photoresistor, which will in turn trigger a 10-15 minute counter before
watering starts.  There will also be a floating switch to keep the pump from completely emptying the water
reservoir, and also a momentary switch for on-demand watering.
Power will be provided by a 12V 2.1A power supply.  60W is more than enough for this size of pump plus the arduino.
