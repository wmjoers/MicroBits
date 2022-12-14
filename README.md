# MicroBits
A collection of some more or less simple micro:bit projects.

## Alarm (blocks)
A motion detection alarm.
* Press A+B
* Place alarm before timer has reached zero.
* When the lock icon is shown, the alarm will go off if moved.

## Candle (blocks)
A magic canndle simulator.
* Snap your fingers to light the canndle.
* Blow it out.

## ScrumPoker (javascript)
A scrum poker app.
* Swap card by pressing A or B.
* Select and hide card by pressing A+B.
* Reveal card by pressen A or B.

## Instrument (blocks)
An experimental "instrument"
* Turn on/off sound with B.
* Tilt device left or right to change sound.

## JingleBells (blocks)
A chistmas gift surprise.
* Press A+B
* Place micro:bit in closed box before timer has reached zero.
* The music will start playing when box is open if the light level is high enough.
 
## SerialMonitor (blocks + requires program on computer)
A small monitor to display a value from the serial port. It also plays a beep if the number is higher than before.
* Connect micro:bit to serialport using USB-cable.
* Start program on computer to send a value (ending with new line character) through the serial port.
* If the value is higher than the last one a beep will be played.
* If the value is higher than 9, the value will scroll past and then show a sad face.
* Replay the value by pressing A.
* Togle sound on/off by pressing B.
* Change brightness of the LEDs by pressing the logo.

## IconChat (blocks)
A small chat program that sends an icon over radio to other micro:bits.
* Use A or B to scroll through the available icons.
* Press A+B to send the selected icon via radio to any micro:bit in range.

## RollingBall (blocks)
Test application for using the accelerometer to control a sprite.
* Tilt the microbit to steer the sprite.
* Press A or B for sound effects.

## Fireplace (blocks)
Fireplace simulator.
* Watch the beautiful fireplace and listen to the sparkling sound it make.
* Smoke not included.

## 2plRockPaperScissors (blocks)
A Rock Paper Scissors game for two players (two micro:bits).
* Use A or B to scroll through the signs.
* Press A+B to send the sign. 
* When both players has selected signs an animation plays on both devices showing the other players sign.
* It then show the result and the current score.
* Press A+B to continue to next round. Both devices continue if one player presses A+B.

## TreasureHunt (blocks)
A multiplayer treasure hunt.
* Press A to start treasure mode. It sends a signal ebery half second.
* Press B to start hunter mode. It displays the signal strength from the treasue or a sad face if no signal was recieved in two seconds.
* Press A+B to go to start mode.

## MultiPlayerSync (blocks)
An example on how to connect several devices and select a master device.
* Start all devices. All units should whow a ghost icon.
* Press A or B to start sync. A = select random master device, B = select the current device as master.
* During sync, all devices should show how many devices they find (including them self).
* After sync is completed a crown-icon will be shown on the selected master unit, the other devices should show a person-icon.

