# libunrar4ios
A Xcode project for building unrar library used in iOS projects.  
  
This project is equivalent to the official unrarlib version 5.3.4. Refer to ```/unrar/version.hpp``` for details.

# Usage
Just open this project in Xcode and build it.  
  
To link the library under both simulator and real devices, use command as follows:  
```lipo -create libunrar-simulator.a libunrar-ios.a -output libunrar.a```.  
  
For detailed documentation, please refer to [this link](http://python-unrar.readthedocs.org/en/latest/unrarlib.html).
