<p align="center">
  <img src="assets/github-profile-banner.svg" alt="Yash Khiste — Robust Autonomy, Control Systems and Model-Based Development" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yash-khiste-95b8371a9"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/yashrk7174?tab=repositories"><img src="https://img.shields.io/badge/Explore-Engineering%20Projects-1F6FEB?style=for-the-badge&logo=github&logoColor=white" alt="Engineering projects"></a>
</p>

## Engineering Profile

M.Sc. Electrical Engineering & Information Technology student at **Otto von Guericke University Magdeburg**, building control and autonomous systems through physics-based modelling, C++ robotics software and verification-first engineering.

| Engineering evidence | Verified result |
|---|---|
| **ROS 2 manipulation** | C++17 executables integrating state monitoring, joint/Cartesian planning, obstacle avoidance, mission sequencing and controlled pose-fault injection |
| **Electric-drive control & V&V** | PMSM–AGV integration, dq current control and cascaded motor-speed/current control verified through automated analytical cross-validation |
| **Control-system design** | Current-loop and outer speed-loop PI controllers designed from explicit bandwidth, tracking and settling requirements |
| **Industrial problem solving** | Brake-joint poka-yoke reduced offline RPT from 15 vehicles to 1–3; PLC logic supported 6+ AGV stations |

## Selected work

| ROS 2 Resilient Manipulation | Electric Drive Control & V&V |
|:---:|:---:|
| [<img src="https://raw.githubusercontent.com/yashrk7174/ROS2-Resilient-Manipulation-Testbed/main/docs/evidence/manipulation_mission_execution.png" alt="Panda manipulation mission" width="470">](https://github.com/yashrk7174/ROS2-Resilient-Manipulation-Testbed) | [<img src="https://raw.githubusercontent.com/yashrk7174/AGV-Electric-Drive-Control-VNV/main/results/control/electric_drive_cascaded_control_verified_model.png" alt="Verified cascaded PMSM current and speed control model" width="470">](https://github.com/yashrk7174/AGV-Electric-Drive-Control-VNV) |
| **ROS 2 · MoveIt 2 · C++17**<br>Collision-aware Panda mission with stale-pose fault detection and reproducible launch workflows. | **MATLAB · Simulink · Simscape · Control · V&V**<br>PMSM–AGV electric drive with verified dq current regulation and cascaded motor-speed control. |

### [Automotive Cruise Control — Model-Based Control](https://github.com/yashrk7174/Automotive-Cruise-Control-Model-Based-Control)

**P → PI → Filtered PID → LQR** development with sensitivity analysis, actuator-limit verification and numerical MATLAB/Simulink agreement. The final constrained LQR test passes stability, tracking and actuator-output checks.

<details>
<summary><strong>More engineering projects</strong></summary>

<br>

- [RoboTwin-Sync](https://github.com/yashrk7174/RoboTwin-Sync-Bidirectional-Digital-Twin-for-Mobile-Manipulator-Robotics) — bidirectional digital-twin framework for mobile-manipulator systems.
- [Digital Signal Processing](https://github.com/yashrk7174/Digital-Signal-Processing-Sampling-Audio-ECG-Analysis) — sampling, reconstruction, spectral analysis, audio, Doppler and ECG processing.
- [Industrial AGV Navigation and Drive Control](https://github.com/yashrk7174/Industrial-AGV-Navigation-and-Drive-Control) — magnetic navigation, deviation monitoring and BLDC drive integration.
- [Brake-Joint Online Pre-Leak Poka-Yoke](https://github.com/yashrk7174/Brake-Joint-Online-Pre-Leak-Testing-Poka-Yoke) — production interlock and online verification preventing no-brake vehicle rollout.

</details>

## Technical stack

<p>
  <img src="https://img.shields.io/badge/ROS%202-Humble-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2">
  <img src="https://img.shields.io/badge/MoveIt%202-Motion%20Planning-2C5F9E?style=flat-square" alt="MoveIt 2">
  <img src="https://img.shields.io/badge/C%2B%2B-17-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++17">
  <img src="https://img.shields.io/badge/Python-Engineering-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/MATLAB-Simulink-EF6C00?style=flat-square" alt="MATLAB and Simulink">
  <img src="https://img.shields.io/badge/Simscape-Physical%20Modeling-0076A8?style=flat-square" alt="Simscape">
  <img src="https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu">
  <img src="https://img.shields.io/badge/CMake-Build-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake">
  <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

<details>
<summary><strong>Verification-first workflow</strong></summary>

<br>

1. Define operating assumptions, interfaces and acceptance criteria.
2. Derive independent reference behaviour from physics or system requirements.
3. Implement the model, controller or planner reproducibly.
4. Exercise nominal, disturbed and failure scenarios.
5. Quantitatively compare observed behaviour against defined references.
6. Record PASS/FAIL results and publish traceable engineering evidence.

</details>

<details>
<summary><strong>Current development roadmap</strong></summary>

<br>

**Robust Autonomy**
- Bounded recovery under perception and execution faults.
- EKF/UKF-based pose estimation and uncertainty monitoring.

**Electric Drive**
- Full Clarke/Park and inverse transformation chain.
- PMSM field-oriented control architecture.
- Inverter and PWM/SVPWM modelling.
- Sensor nonidealities and signal-processing effects.
- C/C++ controller implementation.
- MIL/SIL regression and automated virtual verification.

</details>

## Engineering principle

> A system is not complete when it runs once—it is complete when its assumptions, failure cases and results can be reproduced and defended.

<p align="center">
  <a href="https://www.linkedin.com/in/yash-khiste-95b8371a9">LinkedIn</a> ·
  <a href="https://github.com/yashrk7174?tab=repositories">Repositories</a>
</p>
