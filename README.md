# grandMA3 TouchOSC Remote

This project provides a TouchOSC interface to control grandMA3. On the one hand it provides a replica of the command section of a grandMA3 console, on the other hand it provides the playback section to be used in a live situation. As a special feature there is a sequencer with which grandMA3 can be played like an instrument, which is especially useful in the context of electronic music.

## CommandSection

The CommandSection is a fork of imhofroger, here is the link to the [original project](https://github.com/imhofroger/GMA3_CommandSection). 
<img src="https://github.com/yastefan/GMA3_TouchOSC/blob/main/docs/command_section.png" height="600px"> 
The command section sends OSC messages to the TouchOSC Bridge, which needs to run on the host PC (the PC running grandMA3 onPC). The TouchOSC Bridge works like a keyboard and sends key combinations to grandMA3 onPC. Each keystroke sends F10 before to activate the shortcuts in grandMA3 and F10 afterwards to deactivate the shortcuts again.

### Bringing up the CommandSection


### On PC with GrandMA
-Install TouchOSC Bridge  
-Numlock must be deactive!  
-GrandMA3 KEyboardShortcuts must be Edited! Blue Marked  
<img src="https://github.com/imhofroger/GMA3_TouchOSC/blob/4577f048949c768369e9b8a42510d6a4f3e936cc/GMA3_CommandSection/img/GMA3_Shortcuts-add1.png" height="400px"> 
<img src="https://github.com/imhofroger/GMA3_TouchOSC/blob/4577f048949c768369e9b8a42510d6a4f3e936cc/GMA3_CommandSection/img/GMA3_Shortcuts-add2.png" height="400px"> 


### On Tablet or wherever you run this Command Section
OCS Settings:  
- Host IP: From GrandMA3 OnPC Computer  
- Port: 12101  

TouchOCS Variable must be Edited -> Keyboard Layout  

<img src="https://github.com/imhofroger/GMA3_TouchOSC/blob/2b00b04adf8012c51d29fce68f43a62bf6a87a82/GMA3_CommandSection/img/Screen-key.png" height="300px"> 



