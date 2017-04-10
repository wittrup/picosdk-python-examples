# picosdk-python-examples

picosdk-python-examples contains an example Python module for PicoScope oscilloscopes.

## Getting started

### Prerequisites

* A PicoScope oscilloscope using one of the following PicoScope drivers:
  * ps2000
  * ps2000a
  * ps3000
  * ps3000a
  * ps4000
  * ps4000a
  * ps5000a
  * ps6000
* [Python 2.7](https://www.python.org/download/releases/2.7/) 
* For Streaming mode data collection, the [pytables](http://www.pytables.org/) module is required.
* The test_block and test_streaming examples require [matplotlib](http://matplotlib.org/) and [signal](https://docs.python.org/2/library/signal.html).
* PicoPyScope example has been written for use with [PyQtGraph](http://www.pyqtgraph.org/).

**Notes:** The code is not much different from Python3 and can be easily converted with the [2to3](https://docs.python.org/2/library/2to3.html) utility.
The module has been tested and proved working on Linux (including ARM derivatives), Windows and MacOSX.
For best experience on Windows Python(x,y) suite is recommended.

### Installing drivers

Drivers are available for the following platforms. Refer to the subsections below for further information.

#### Windows

* Download the PicoSDK (32-bit or 64-bit) driver package installer from our [Downloads page](https://www.picotech.com/downloads).

#### Linux

* Follow the instructions from our [Linux Software & Drivers for Oscilloscopes and Data Loggers](https://www.picotech.com/downloads/linux) to install the required driver packages for your product.

#### Mac OS X

* Visit our [Downloads page](https://www.picotech.com/downloads) and download the PicoScope Beta for Mac OS X application.

### Programmer's Guides

You can download Programmer's Guides providing a description of the API functions for the relevant PicoScope or PicoLog driver from our [Documentation page](https://www.picotech.com/library/documentation).

## Obtaining support

Please visit our [Support page](https://www.picotech.com/tech-support) to contact us directly or visit our [Test and Measurement Forum](https://www.picotech.com/support/forum17.html) to post questions.

## Copyright and licensing

picosdk-python-examples is Copyright (C) 2017 Pico Technology Ltd. All rights reserved. See LICENSE.md for license terms. 

*PicoScope* and *PicoLog* are registered trademarks of Pico Technology Ltd. 

*Windows* is a registered trademark of Microsoft Corporation. 

*Mac* and *OS X* are registered trademarks of Apple, Inc. 

*Linux* is the registered trademark of Linus Torvalds in the U.S. and other countries.

## Contributing

Contributions are welcome. Please refer to our [guidelines for contributing](.github/CONTRIBUTING.md) for further information.
