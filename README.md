# PicoSatellite ADCS

Design, simulation, and experimental validation of a hybrid attitude determination and control system (ADCS) for a PocketQube satellite using gravity-gradient stabilization and magnetorquer-assisted control.

---

# Project Overview

This project was developed through the Wentworth PicoSat Initiative as part of the design and validation of a hybrid spacecraft attitude control architecture for a PocketQube satellite platform.

The system combines:

- Passive gravity-gradient stabilization
- Deployable tethered boom dynamics
- Magnetorquer-assisted control
- Simulation-driven design
- Experimental deployment validation

The objective of the system is to achieve stable Earth-oriented attitude control within the severe mass, power, and volume constraints of the PocketQube platform.

---

# System Architecture

The attitude control system uses a hybrid control approach:

## Passive Control
A deployable gravity-gradient boom extends a tethered mass below the spacecraft, increasing the system moment of inertia and generating a restoring torque due to Earth’s gravity gradient.

## Active Control
Embedded magnetorquers provide active control authority and correction of residual yaw drift within Earth’s magnetic field.

---

# Project Components

## Gravity-Gradient Boom System
- Deployable tethered boom architecture
- Tungsten boom mass optimization
- Tether spool geometry development
- Deployment stability analysis

## Simulation & Dynamics
- Quaternion-based rotational dynamics
- LVLH frame transformations
- Tether force modeling
- Variable-step Runge-Kutta integration
- Gravity-gradient torque analysis

## Experimental Validation
- Scaled tether deployment experiments
- Spool geometry testing
- Deployment disturbance analysis
- Tension spike mitigation

---

# Technical Topics

- Spacecraft Attitude Dynamics
- Gravity-Gradient Stabilization
- Magnetorquer Control
- Orbital Mechanics
- Quaternion Kinematics
- Tether Dynamics
- Aerospace Simulation
- Embedded Space Systems
- Experimental Validation
- Rapid Prototyping

---

# Tools & Software

- SolidWorks
- MATLAB
- Simulink
- Embedded Systems Development
- Additive Manufacturing
- Experimental Test Design

---

# Research Paper

This repository includes the AIAA Region I Student Conference paper:

**“Design and Validation of a Gravity-Gradient Boom Arm for Hybrid Attitude Control of a PocketQube Satellite”**

Topics investigated include:
- deployable boom dynamics
- passive spacecraft stabilization
- tether deployment behavior
- orbital attitude simulation
- experimental spool validation

---

# Key Engineering Challenges

- Maintaining stability within PocketQube size constraints
- Reducing deployment-induced disturbances
- Minimizing transient tether tension spikes
- Achieving reliable spool deployment behavior
- Integrating passive and active attitude control systems

---

# Experimental Results

Testing demonstrated that spool geometry significantly affects deployment stability and transient tension behavior.

Simulation and physical testing showed:
- bounded libration behavior
- stable nadir-pointing performance
- reduced disturbance through optimized spool geometries
- successful deployment stabilization concepts

---

# Future Development

- Magnetorquer integration
- Flight-ready deployment hardware
- IMU/magnetometer feedback integration
- RTOS-based onboard control systems
- Higher-fidelity orbital perturbation modeling

---

# Acknowledgments

Developed through the Wentworth PicoSat Initiative.

Conference work presented at the AIAA Region I Student Conference.
