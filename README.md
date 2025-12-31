# DJI RC-N1 Simulator (GUI Version) | 大疆 RC-N1 模拟器 GUI 整合版

> 🎮 Turn your DJI RC-N1 controller into a virtual Xbox 360 gamepad for PC simulators.
> 
> 🎮 将你的大疆 RC-N1 遥控器变身为电脑上的 Xbox 360 手柄，畅玩各类飞行模拟器。

---
<p align="center">
  <img src="screenshot.png" alt="软件界面预览" width="600">
</p>
## 📖 Introduction (简介)

This application allows you to use the **DJI RC-N1** remote controller (compatible with Mini 2/3, Air 2S, Mavic 3, etc.) as a standard **Xbox 360 Controller** on Windows.

It is designed for FPV simulators like **Uncrashed**, **Liftoff**, **DRL**, and **DCL**.

**Key Features:**
* **GUI Interface:** User-friendly graphical interface with visual feedback.
* **Plug & Play:** Packaged as a single `.exe` file. No Python environment required.
* **Custom Mapping:** Fully customizable buttons (B1/B2/Fn), gimbal wheel, and flight mode switch.
* **Smart Detection:** Automatically detects if the required driver is missing and guides you to the download page.

本项目是一个 Windows 应用程序，允许你将 **DJI RC-N1** 遥控器作为标准游戏手柄在电脑上使用。特别适合用于练习 FPV 模拟器。

**主要特点：**
* **图形化界面**：拥有可视化的操作面板，状态一目了然。
* **单文件运行**：只有一个 `.exe` 文件，无需安装 Python 环境。
* **自定义映射**：支持自定义 B1/B2/Fn 键、云台波轮以及三档飞行模式开关。
* **智能检测**：程序启动时会自动检测驱动，若未安装会自动打开官方下载页面。

---

## ⚙️ Prerequisites (必要环境)

To run this simulator, you **MUST** install the virtual gamepad driver first.
运行本模拟器前，您**必须**先安装虚拟手柄驱动。

**👉 Driver Download (驱动下载):**
**[ViGEmBus Latest Release (Official GitHub)](https://github.com/nefarius/ViGEmBus/releases/latest)**

*Please download and install `ViGEmBus_Setup_x.x.x.exe` from the link above.*
*请点击上方链接，下载并安装最新的 `ViGEmBus_Setup_x.x.x.exe`。*

---

## 📥 App Download (软件下载)

Go to the **[Releases](../../releases)** page to download the simulator:
前往右侧 **[Releases](../../releases)** 页面下载模拟器主程序：

* **DJI_Sim_VIP.exe**

---

## 🛠️ How to Use (使用方法)

1.  **Install Driver:** Ensure you have installed **ViGEmBus** (link above).
2.  **Connect Controller:** Power on your RC-N1 and connect it to PC via USB.
3.  **Run Simulator:** Double-click `DJI_Sim_VIP.exe`.
4.  **Select Port:** Choose the port named `DJI USB VCOM For Protocol` and click **"Start" (启动映射)**.
5.  **Enjoy:** Open your game (e.g., Uncrashed), set controller to "Gamepad", and fly!

1.  **安装驱动**：确保已安装 **ViGEmBus** 驱动（见上文链接）。
2.  **连接遥控器**：开启 RC-N1 遥控器，用 USB 线连接电脑。
3.  **运行软件**：双击运行 `DJI_Sim_VIP.exe`。
4.  **选择端口**：选择名为 `DJI USB VCOM For Protocol` 的端口，点击 **“启动映射”**。
5.  **开始飞行**：打开游戏，将控制方式改为“手柄”，即可开始练习。

---

## 🎮 Default Controls (默认按键)

| RC-N1 Input | Xbox Output | Suggested Function |
| :--- | :--- | :--- |
| **Sticks** | Sticks | Pitch/Roll/Yaw/Throttle |
| **B1 (Back Left)** | RT (Right Trigger) | Throttle / Confirm |
| **B3 (Face Right)**| Y Button | Reset Drone |
| **Fn (Back Right)**| RB (Right Bumper) | Auxiliary |
| **Gimbal Wheel** | D-Pad Up/Down | Menu Navigation |
| **Mode Switch** | LB (Left Bumper) | Mode Toggle / Arm |

*Note: You can customize these mappings inside the application.*
*注：你可以在软件界面中自由修改这些映射配置。*

---

## ⚖️ License & Credits (许可与致谢)

**Core Logic based on:** [DJI_RC-N1_SIMULATOR_FLY_DCL](https://github.com/IvanYaky/DJI_RC-N1_SIMULATOR_FLY_DCL) by **IvanYaky**.

This project uses code licensed under the **Apache License 2.0**.
本项目核心逻辑引用自 IvanYaky 的开源项目，遵循 **Apache License 2.0** 协议。

**Driver Credit:**
Virtual Gamepad emulation provided by [ViGEmBus](https://github.com/nefarius/ViGEmBus) by **nefarius**.

---

## ⚠️ Disclaimer (免责声明)

This software is for educational and simulation purposes only. DO NOT use it for real-world flight control. The author is not responsible for any damage caused by the use of this software.

本软件仅供模拟器练习和学习交流使用，严禁用于任何实际飞行控制。作者不对因使用本软件造成的任何损失负责。
