---
layout: post
title: "Arduino Smartcar"
author: Markus Wrang
categories: experience
tags: [Arduino, Android, Gradle, C, Java]
image: /img/smartcar_img.jpg
image_alt: Arduino Smartcar
code: https://github.com/firsou/arduino-smartcar
---

The arduino Smartcar is an embedded system written in Arduino, the car got a connected Android Application
where you can control the car. You can manually control it with different methods or use an autonomous mode where the car will
avoid obstacles. The different control methods for the car is a Joystick mode, D-PAD and tilt control.

### App

It's an app made with Java witch make a connection to the car via bluetooth. After you connect to the car you will be able to control the car
with the different driving modes that wee implemented. You can also choose to use the autonomous mode where the car drives by itself.
In the app you also get have a radar witch will scan the area infront of the car and show any obstacles.

### Hardware

The car itself makes use of several hardware components, most importantly:

- Accelerometer
- Motor
- 4 Ultrasonic Sensors
- One Servo Motor
- Lots of wires
