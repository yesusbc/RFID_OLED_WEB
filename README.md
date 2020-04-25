# RFID_OLED_WEB
Instead of calling the roll traditionally, this method propose system that uses students cards' ID, an RFID lector and an OLED display for a nice human interaction.

A very cheap and easy system, and the best of all... it's all mounted only on a *Node MCU*.


### Circuit Overview
<img src="https://github.com/yesusbc/RFID_OLED_WEB/blob/master/Sample%20Images/full%20view%202.jpeg" alt="Overview" width="480" height="640">


### 1. Acronym of career is presented
ITC (Ingeniero en Tecnologías Computacionales, _Engineer in Computational Technologies_)
<img src="https://github.com/yesusbc/RFID_OLED_WEB/blob/master/Sample%20Images/OLED_Idle.jpeg" alt="Overview" width="640" height="480">

### 2. Recognize an student RFID card
When an student approachs and place its card above the lector, the circuit will recognize the credential and it will display a sand clock, which means it's loading.
<img src="https://github.com/yesusbc/RFID_OLED_WEB/blob/master/Sample%20Images/OLED_waiting.jpeg" width="640" height="480">

### 3. Send data to database
A check mark will appear when the reading was succesfull and the data was sent to database.
<img src="https://github.com/yesusbc/RFID_OLED_WEB/blob/master/Sample%20Images/OLED_done.jpeg" alt="Overview" width="640" height="480">

