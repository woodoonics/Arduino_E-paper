Two examples to use with the Arduino micro compatible E-paper board.
The board is available to purchase from Woodoonics store on Tindie:
https://www.tindie.com/products/woodoonics/arduino-micro-compatible-e-paper-e-ink-board/

Example codes:
- EPD1in54C makes use of the Arduino EPD library by Asuki Kono. Please add this library to your Arduino IDE before compiling this code.
Using this code it's possible to send a picture to be shown on the E-paper display.
First use the IMG2LCD program (which can be downloaded for free from https://image2lcd.software.informer.com/3.2/) to convert a photo to an array. Choose 152 by 152 pixel photo size.
Then paste the array inside the imagedata.cpp file and upload the code to the board.

- The GxEPD example makes use of the GxEPD library by Jean-Marc Zingg. Please add the latest version of this library to your Arduino IDE before attempting to compile this code.

Enjoy!
