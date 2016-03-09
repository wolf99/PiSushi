PiDie Demo Software
===================

PiDie LEDs are on physical pins as follows:
    Led1: 7  - GPIO - 4
    Led2: 11 - GPIO - 17
    Led3: 12 - GPIO - 18
    Led4: 13 - GPIO - 21 for model A, 27 for later models	
    Led5: 15 - GPIO - 22
    Led6: 16 - GPIO - 23
    Led7: 18 - GPIO - 24
    Led8: 22 - GPIO - 25
    Led9: 8  - GPIO - 14

Buttons on physical pins as follows:
    Red: 21    - GPIO - 9
    Green: 19  - GPIO - 10
    Yellow: 24 - GPIO - 8
    Blue: 26   - GPIO - 7


Scratch Programs:

GPIOLEDs.sb	Uses the number keys on keyboard to turn same number LED on and off
GPIOButtons.sb	Switches on the LED next to each button when the button is pressed
Simon_SDM.sb	A complete Simon game: By Sjoerd Dirk Meijer - @fromScratchEd from http://scratch.mit.edu/projects/11939445/

Python Demo:
TrafficLights.py	Uses LEDs 1, 2 and 3 to sequence traffic lights
