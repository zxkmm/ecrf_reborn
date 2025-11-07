# ARCHIVED
I archived this repo since the original developer already made an up to date version of opensource firmware.

# original README
```
# ecrf_reborn
This repo fine-tuned outdated dependents and make ecrf-v2 can compile and flash normally

# NOTE
## This repo exists ONLY because the original ECRF project is abandened (or at least paused developing for long), and many dependents it is using, are changing, so not compatible anymore.
## and sadly I still paid and own the device
## So I rolled many lib back to the last version that the last(*latest*) version of ECRF works with. 
## SO I DIDN'T WROTE ANY CODE IN THIS REPO. THEY BELONGS TO WHOEVER MADE IT.

## How to use:
1. Clone this repo
2. copy all the folders in arduino_libs into the Arduino lib dir, usually it's ~/Arduino/libraries
    NOTE: I fine tuned the libs in it, thus if you have lib has same name, DELETE yours first, then do the copy step above.
    NOTE: I fine tuned the libs in it, thus if arduino ask you to update libs, DO NOT UPDATE THEM
3. open the latest_ecrf/EvilCrow-RFv2/EvilCrow-RFv2.ino in Arduino IDE, following official guide to set board info and port, then flash
4. Following official guide to put sdcard content into your sdcard.
5. Star this repo so when you want it back, you can find it.

# Q&A
Q: Why this   
A: The original project were abandoned (or at least paused developing for long), which caused some of the libs not compatible with ecrf code anymore. 
The sad part is I still paid and own the device.
So I created this repo that contains those libs that stays at the last version which can compile ecrf fw.



Q: Why not submodule, which looks less like you stealing code from others  
A: I lazy.
```
