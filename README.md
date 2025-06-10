## Welcome to the Fullstack Embodied AI Guide\!
<p align="center">
  <img width="300" alt="f939a2605d4f7fcccc692090e379753" src="https://github.com/user-attachments/assets/6145c4a7-bf46-4650-b57c-e90c18fe220e" />
</p>


This repository serves as a comprehensive, step-by-step guide to building, configuring, and operating your **LeRobot SO-ARM101 Robotic Arm**. Our mission is to demystify robotics and AI by providing a hands-on learning experience, culminating in the implementation of advanced control techniques like **Diffusion Policy**, **ACT** and so on.

Whether you're a beginner curious about robotics or an enthusiast eager to dive into imitation learning, this guide is designed to help you bring your SO-ARM101 to life and equip it with intelligent control.

-----

## Getting Started: Acquiring Your SO-ARM101
<p align="center">
  <img src="https://github.com/user-attachments/assets/f6f5992b-b02d-47b0-93b9-468cc09bba3a" width="400px" style="display: inline-block; margin: 0 10px;">
  <img src="https://github.com/user-attachments/assets/06e1a231-ca57-4cd7-82fa-a757346b884e" width="400px" style="display: inline-block; margin: 0 10px;">
</p>

If you don't yet have a LeRobot SO-ARM101, you have a few options to get started:

  * **Build Your Own:** Explore the official GitHub repository for the SO-ARM100 (the core design for the 101) to find detailed build instructions and component lists:
    [TheRobotStudio/SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100)
  * **Purchase a Kit:** You can often find ready-to-assemble kits or pre-built arms on platforms like Amazon or Taobao for less than £200.

-----

## Setting Up Your Robotic Arm

Once you have your SO-ARM101 kit and components ready, let's dive into the exciting world of robotic arm control\!

### 1\. Pre-configuring Servo IDs and Parameters

Properly setting up your servo motors is a crucial first step for stable and reliable arm operation.

  * **Download the Servo Configuration Tool:**
    You'll need the `FD1.9.8.5` servo debugging tool to configure your servo IDs and parameters.
    [Download FD1.9.8.5 (250425).zip](https://gitee.com/ftservo/fddebug/blob/master/FD1.9.8.5\(250425\).zip)
    You Should be able to see a page like below:
    ![image](https://github.com/user-attachments/assets/c2102d50-6846-43e8-a11e-6e051fc7278d)

  * **Follow the Configuration Tutorial:**
    [LeRobot SO-ARM101 Robotic Arm - Assembly and Setup Guide](https://www.youtube.com/watch?v=70GuJf2jbYk)

## What's Next in this Guide?

This guide will progressively lead you through:

  * **Hardware Assembly & Wiring:** Detailed instructions for putting your SO-ARM101 together.
  * **Basic Control & Calibration:** Getting your arm to move with simple commands.
  * **Software Environment Setup:** Preparing your computer for advanced robotics development (Python, relevant libraries).
  * **Introduction to Diffusion Policy:** Understanding the theory behind this powerful imitation learning technique.
  * **Implementing Diffusion Policy:** Practical steps to collect data, train models, and deploy Diffusion Policy on your SO-ARM101 for various tasks.
  * **Troubleshooting & Advanced Tips:** Common issues and how to resolve them.

-----

## Contributing

We welcome contributions to make this guide even better\! If you have suggestions, corrections, or want to add a new section (e.g., a verified servo configuration tutorial\!), please feel free to open an issue or submit a pull request.

-----

## License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).
