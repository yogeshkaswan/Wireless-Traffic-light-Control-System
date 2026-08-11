# 🚦 Wireless Traffic Light Control System

## 📌 Description

The Wireless Traffic Light Control System is a Java-based application designed to simulate the operation and control of traffic signals wirelessly.

The system manages traffic light states, controls signal timing, and coordinates traffic movement using predefined control logic. It demonstrates how programming concepts can be applied to simulate a smart traffic management system.

## ✨ Features

* 🚦 Control traffic light signals
* 🔄 Automatically switch between Red, Yellow, and Green
* ⏱️ Manage signal timing
* 📡 Simulate wireless signal control
* 🚗 Coordinate traffic movement
* 📊 Display current traffic light status
* ⚠️ Handle invalid user input
* 🔁 Continuous signal operation

## 🛠️ Technologies Used

* Java
* Object-Oriented Programming
* Java Collections Framework
* Multithreading
* Exception Handling
* Java Date and Time API

## 📚 Concepts Used

* Classes and Objects
* Encapsulation
* Inheritance
* Conditional Statements
* Loops
* Methods
* Exception Handling
* Multithreading
* Data Structures

## ⚙️ System Working

The system simulates a traffic intersection where traffic signals operate in a controlled sequence:

```text
        🚦 Traffic Signal

            RED
             ↓
          YELLOW
             ↓
           GREEN
             ↓
          YELLOW
             ↓
            RED
```

The signal automatically changes its state after a predefined time interval.

## 📂 Project Structure

```text
Wireless-Traffic-Light-Control-System/
│
├── src/
│   ├── Main.java
│   ├── TrafficLight.java
│   ├── TrafficController.java
│   └── TrafficLightSystem.java
│
├── README.md
├── .gitignore
└── LICENSE
```

## ▶️ How to Run

1. Clone the repository.
2. Open the project in IntelliJ IDEA, Eclipse, or VS Code.
3. Open the `src` folder.
4. Compile the Java files.
5. Run `Main.java`.
6. Follow the instructions displayed in the console.

## 💻 Example Output

```text
========================================
   WIRELESS TRAFFIC LIGHT CONTROL SYSTEM
========================================

Traffic Signal: RED
Waiting...

Traffic Signal: GREEN
Traffic can move.

Traffic Signal: YELLOW
Prepare to stop.

Traffic Signal: RED
Traffic has stopped.
```

## 🚀 Future Enhancements

* Add a graphical user interface
* Add multiple traffic intersections
* Add emergency vehicle priority
* Add pedestrian crossing control
* Add vehicle density detection
* Add IoT sensor integration
* Add real wireless hardware communication
* Add database-based traffic monitoring
* Add real-time traffic analytics

## 🎯 Objective

The main objective of this project is to demonstrate the working of an automated traffic signal control system using Java programming concepts and simulated wireless communication.

## 👨‍💻 Project Type

Java Console-Based Simulation Project

## 📄 License

This project is available under the MIT License.
