<img width="2760" height="1400" alt="esp32_project_ideas_repo_banner" src="https://github.com/user-attachments/assets/022dd467-66fc-488a-a774-8eda5845e28a" />

# ESP32 Project Ideas

This **ESP32 Project Ideas** repository is created to guide and help you with your related or similar projects.

You can **modify the code** according to your requirements or use it as provided.

> **All codes have been tested and are working.**

Enjoy your programming journey and build something different! 🚀

---

## 📌 Wiring Connections

> **Note:** Wiring connections are provided for **Laboratory 2** activities.

### 🔹 Lab 2.1 — UART Communication

| ESP32 A       | Connection | ESP32 B       |
| ------------- | :--------: | ------------- |
| GPIO 17 — TX2 |      →     | GPIO 16 — RX2 |
| GPIO 16 — RX2 |      →     | GPIO 17 — TX2 |
| GND           |      →     | GND           |

---

### 🔹 Lab 2.2 — UART Communication

| ESP32 A      | Connection | ESP32 B      |
| ------------ | :--------: | ------------ |
| GPIO 17 — TX |      →     | GPIO 16 — RX |
| GPIO 16 — RX |      →     | GPIO 17 — TX |
| GND          |      →     | GND          |

---

### 🔹 Lab 2.3 — I²C Communication

| ESP32 Master  | Connection | ESP32 Slave   |
| ------------- | :--------: | ------------- |
| GPIO 21 — SDA |      →     | GPIO 21 — SDA |
| GPIO 22 — SCL |      →     | GPIO 22 — SCL |
| GND           |      →     | GND           |

---

### 🔹 Lab 2.4 — I²C Bus Scanner

| ESP32         | Connection | OLED |
| ------------- | :--------: | ---- |
| 3V3           |      →     | VCC  |
| GND           |      →     | GND  |
| GPIO 21 — SDA |      →     | SDA  |
| GPIO 22 — SCL |      →     | SCL  |

> **Note:** A common SSD1306 I²C OLED uses address `0x3C`. The actual address may vary depending on the module.

---

### 🔹 Lab 2.6 — SPI Communication

| Master ESP32   | Connection | Slave ESP32    |
| -------------- | :--------: | -------------- |
| GPIO 18 — SCK  |      →     | GPIO 18 — SCK  |
| GPIO 23 — MOSI |      →     | GPIO 23 — MOSI |
| GPIO 19 — MISO |      →     | GPIO 19 — MISO |
| GPIO 5 — CS    |      →     | GPIO 5 — CS    |
| GND            |      →     | GND            |

---

## 📚 Laboratory Summary

| Laboratory  | Communication Protocol | Main Components |
| ----------- | ---------------------- | --------------- |
| **Lab 2.1** | UART                   | 2 × ESP32       |
| **Lab 2.2** | UART                   | 2 × ESP32       |
| **Lab 2.3** | I²C                    | 2 × ESP32       |
| **Lab 2.4** | I²C                    | ESP32 + OLED    |
| **Lab 2.6** | SPI                    | 2 × ESP32       |

---

### 💡 Important

For the communication laboratories, make sure that:

* The **GND connections are shared** between communicating devices.
* **TX connects to RX** for UART.
* **SDA connects to SDA** and **SCL connects to SCL** for I²C.
* **MOSI, MISO, SCK, and CS** are connected correctly for SPI.
* Check the voltage requirements of your modules before connecting them.

---

⭐ **Feel free to use, modify, and improve these projects.**

**Happy coding and happy building! 🚀**

