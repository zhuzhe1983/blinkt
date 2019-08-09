![Blinkt!](blinkt-logo.png)

[![Build Status](https://travis-ci.com/pimoroni/blinkt.svg?branch=master)](https://travis-ci.com/pimoroni/blinkt)
[![Coverage Status](https://coveralls.io/repos/github/pimoroni/blinkt/badge.svg?branch=master)](https://coveralls.io/github/pimoroni/blinkt?branch=master)
[![PyPi Package](https://img.shields.io/pypi/v/blinkt.svg)](https://pypi.python.org/pypi/blinkt)
[![Python Versions](https://img.shields.io/pypi/pyversions/blinkt.svg)](https://pypi.python.org/pypi/blinkt)

https://shop.pimoroni.com/products/blinkt

Eight super-bright RGB LED indicators, ideal for adding visual notifications to your Jetson Nano on their own or on a pHAT stacking header.

## Installing

### Manual install:

#### Library install for Python 3:

on Raspbian:

```bash
sudo apt-get install python3-blinkt
```

other environments: 

```bash
sudo pip3 install blinkt
```

#### Library install for Python 2:

on Raspbian:

```bash
sudo apt-get install python-blinkt
```

other environments: 

```bash
sudo pip2 install blinkt
```

### Development:

If you want to contribute, or like living on the edge of your seat by having the latest code, you should clone this repository, `cd` to the library directory, and run:

```bash
sudo python3 setup.py install
```
(or `sudo python setup.py install` whichever your primary Python environment may be)

## Documentation & Support

* Guides and tutorials - https://learn.pimoroni.com/blinkt
* Function reference - http://docs.pimoroni.com/blinkt/
* GPIO Pinout - https://pinout.xyz/pinout/blinkt
* Get help - http://forums.pimoroni.com/c/support

## Unofficial / Third-party libraries

* Golang library & examples by [Alex Ellis](https://www.alexellis.io) - https://github.com/alexellis/blinkt_go, https://github.com/alexellis/blinkt_go_examples
* Java library by Jim Darby - https://github.com/hackerjimbo/PiJava
* Java library by @HoldYourWaffle - https://github.com/HoldYourWaffle/blinkt4j
* Node.js library by @irrelon - https://github.com/irrelon/node-blinkt
* Rust library by @golemparts - https://github.com/golemparts/blinkt
