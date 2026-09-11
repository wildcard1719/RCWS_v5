<div align="center">

### Mechanical Design Handbook

# 3D Printed Remote Controlled<br>Weapon System v5

<img src="img/front.png" alt="RCWS v5" width="460">

## WILDCARD

</div>

---

# Table of contents

1. [Overview](#overview)
2. [System Architecture](#system-architecture)
3. [Drive system](#drive-system)
   - [3-1. Main frame & Neck frame](#main-frame-neck-frame)
   - [3-2. Main actuator](#main-actuator)
   - [3-3. 3D printed azimuth bearing](#3d-printed-azimuth-bearing)
   - [3-4. Tripod](#tripod)
4. [Launcher](#launcher)
   - [4-1. Feeder](#feeder)
   - [4-2. Accelerator](#accelerator)
5. [EOTS](#eots)
   - [5-1. EOTS actuator](#eots-actuator)
   - [5-2. Camera frame](#camera-frame)
6. [Electronic control](#electronic-control)

<a id="overview"></a>
# 1. Overview

The RCWS (Remote Controlled Weapon System) v5 prototype is one of several 3D-printed RCWS projects. The goal of this project is to demonstrate an electro-optical fire-control system at a range of approximately 30 meters. The RCWS v5 was designed so that all mechanical parts, except for electronic components and bearings, can be fabricated using an Ender 3 V2 3D printer.  
This document presents the mechanical design and assembly of the RCWS v5.

<p align="center">
  <img src="img/front.png" alt="RCWS v5 assembled" width="40%">
  &nbsp;&nbsp;
  <img src="img/asm.png" alt="RCWS v5 exploded view" width="40%">
</p>

<p align="center"><em>Figure 1.</em></p>

<a id="system-architecture"></a>
# 2. System Architecture

The RCWS v5 consists of four main subsystems: the drive system, launcher, electro-optical targeting system (EOTS), and electronic control system.

<p align="center">
  <img src="img/asm2_texted.png" alt="RCWS v5 system architecture" width="78%">
</p>

<p align="center"><em>Figure 2.</em></p>

The drive system and EOTS each use two worm-gear actuators. The launcher and camera can be controlled independently. This four-axis architecture supports fire-control operation against moving targets and at extended ranges.

All mechanical parts of the RCWS v5 are designed to be printable on an Ender 3 V2 3D printer. The largest component, Main Frame (`Main_Frame`), has a bounding box of 180 × 145 × 248 mm.

<a id="drive-system"></a>
# 3. Drive System

The drive system is a two-axis pan-tilt chassis comprising the main frame, neck frame, two worm-gear actuators, a 3D-printed azimuth bearing, and a tripod.

<a id="main-frame-neck-frame"></a>
## 3-1. Main Frame & Neck Frame

<p align="center">
  <img src="img/main_neck_frame_1.png" alt="Main frame and neck frame" width="40%">
  &nbsp;&nbsp;
  <img src="img/main_neck_frame_2.png" alt="Main frame and neck frame exploded view" width="40%">
</p>

<p align="center"><em>Figure 3.</em></p>

**&lt;Non 3D printed Parts&gt;**  
M2 x 10mm bolt  
M3 x 10mm bolt  
M3 x 12mm bolt  
M3 hex nut  
M4 x 15mm bolt  
limit switch  
6805ZZ bearing

<a id="main-actuator"></a>
## 3-2. Main Actuator


<table>
  <tr>
    <td width="50%" align="center"><img src="img/main_actuator_1.png" alt="Main actuator" width="100%"></td>
    <td width="50%" align="center"><img src="img/main_actuator_2.png" alt="Main actuator" width="100%"></td>
  </tr>
  <tr>
    <td width="50%" align="center"><img src="img/main_actuator_3.png" alt="Main actuator exploded view" width="100%"></td>
    <td width="50%" align="center"><img src="img/main_actuator_4.png" alt="3D-printed main actuator" width="100%"></td>
  </tr>
</table>

<p align="center"><em>Figure 4.</em></p>

**&lt;Non 3D printed Parts&gt;**  
NEMA17 stepper motor  
M3 x 5mm bolt  
M3 hex nut  
M4 x 15mm bolt  
M4 hex nut  
6809ZZ bearing  
MR128ZZ bearing

<a id="3d-printed-azimuth-bearing"></a>
## 3-3. 3D-Printed Azimuth Bearing

The entire frame and beads are 3D printed because of cost of bearing.

<p align="center">
  <img src="img/bearing_1.png" alt="3D printed azimuth bearing" width="40%">
  &nbsp;&nbsp;
  <img src="img/bearing_2.png" alt="3D printed azimuth bearing exploded view" width="40%">
</p>

<p align="center"><em>Figure 5.</em></p>

**&lt;Non 3D printed parts&gt;**  
M3 x 12mm bolt  
M3 hex nut  
M4 x 15mm bolt  
M4 x 20mm bolt  
M4 hex nut

<a id="tripod"></a>
## 3-4. Tripod

<p align="center">
  <img src="img/tripod.png" alt="Tripod" width="70%">
</p>

<p align="center"><em>Figure 6.</em></p>

**&lt;Non 3D printed parts&gt;**  
M4 x 15mm bolt  
M4 hex nut

<a id="launcher"></a>
# 4. Launcher

The launcher primarily consists of a feeder and an accelerator. An EOTS mount is located on the lower section of the assembly.

<p align="center">
  <img src="img/launcher_1.png" alt="Launcher" width="82%"><br>
  <img src="img/launcher_2.png" alt="Launcher exploded view" width="82%">
</p>

<p align="center"><em>Figure 7.</em></p>

<a id="feeder"></a>
## 4-1. Feeder

<p align="center">
  <img src="img/feeder_1.png" alt="Feeder" width="40%">
  &nbsp;&nbsp;
  <img src="img/feeder_2.png" alt="Feeder exploded view" width="40%">
</p>

<p align="center"><em>Figure 8.</em></p>

**&lt;Non 3D printed parts&gt;**  
NEMA17 stepper motor  
35mm stroke 12v solenoid  
M2 x 10mm bolt  
M3 x 5mm bolt  
M3 x 10mm bolt  
M4 x 15mm bolt  
M4 hex nuts

<a id="accelerator"></a>
## 4-2. Accelerator

<p align="center">
  <img src="img/accelerator_1.png" alt="Accelerator" width="40%">
  &nbsp;&nbsp;
  <img src="img/accelerator_2.png" alt="Accelerator exploded view" width="40%">
</p>

<p align="center"><em>Figure 9.</em></p>

**&lt;Non 3D printed parts&gt;**  
2204 2300kv BLDC motor  
OD 26mm ID 20mm pvc pipe  
limit switch  
M3 x 7mm bolt  
M3 hex nut  
M4 x 15mm bolt  
M4 hex nut

<a id="eots"></a>
# 5. EOTS

The EOTS features a cable-driven camera zoom mechanism and an adjustable rangefinder zero. It is mounted on a two-axis gimbal, and each axis can be calibrated using an individual limit switch.

<p align="center">
  <img src="img/EOTS_1.png" alt="EOTS" width="40%">
  &nbsp;&nbsp;
  <img src="img/EOTS_2.png" alt="EOTS exploded view" width="40%">
</p>

<p align="center"><em>Figure 10.</em></p>

<a id="eots-actuator"></a>
## 5-1. EOTS Actuator

<p align="center">
  <img src="img/mini_actuator_1.png" alt="EOTS actuator" width="40%">
  &nbsp;&nbsp;
  <img src="img/mini_actuator_2.png" alt="EOTS actuator exploded view" width="40%">
</p>

<p align="center"><em>Figure 11.</em></p>

**&lt;Non 3D printed parts&gt;**  
M3 x 5mm bolt  
M3 x 10mm bolt  
M3 hex nut  
MR128ZZ bearing  
6805ZZ bearing

<a id="camera-frame"></a>
## 5-2. Camera Frame

<p align="center">
  <img src="img/camera_1.png" alt="Camera frame exploded view" width="40%">
  &nbsp;&nbsp;
  <img src="img/camera_2.png" alt="Camera zoom mechanism" width="40%">
</p>

<p align="center"><em>Figure 12.</em></p>

<p align="center">
  <img src="img/camera_3.png" alt="Camera frame" width="72%">
</p>

<p align="center"><em>Figure 13.</em></p>

**&lt;Non 3D printed parts&gt;**  
sg90 servo motor  
raspberry pi HQ camera  
limit switch  
M2 x 3mm bolt  
M2 x 12mm bolt  
M2 hex nut  
M3 x 10mm bolt  
M3 x 25mm bolt  
M3 hex nut

<a id="electronic-control"></a>
# 6. Electronic Control

Unfortunately, most of the documentation related to the electronic control system has been lost. An Arduino was used to control the stepper motors and interpret PWM signals from the RC transmitter and receiver, while a Raspberry Pi 4 was used for image processing.

<p align="center">
  <img src="img/electronics_1.png" alt="Electronic control board" width="72%">
</p>

<p align="center"><em>Figure 14.</em></p>

<p align="center">
  <img src="img/electronics_2.png" alt="RCWS v5 prototype" width="72%">
</p>

<p align="center"><em>Figure 15.</em></p>

---

<div align="center">

Made by **wildcard**  
[github.com/wildcard1719](https://github.com/wildcard1719) · wildcard1719@gmail.com

</div>
