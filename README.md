# W and M Casino

## Description
We created a casino simulator consisting of 2 games - BlackJack and European Roulette. The project uses TCP Client-Server communication, each game that player begins to play is a separate thread.
Every player's balance change is saved to database as well as the player's login and password. Players may be connected to the server on specified port and IP and use chat to talk with each other.

## Installation
### Requirements
- Java 21 or newer
- Maven
### Development setup
```shell
git clone https://github.com/xVilly/kasyno.git
# Client:
cd kasyno/kasynoclient
mvn clean install
mvn javafx:run

# Server:
cd kasyno/kasynoserver
cd src/main/java/com/example
java Server.java
```
### Deployment (JAR)
- Use within kasynoclient or kasynoserver project
```shell
mvn clean package
```
## Screenshots 
### BlackJack

![blackjack1](https://github.com/user-attachments/assets/043d5e92-73ff-4e8d-be43-83759abcf1d5)
---
![blackjack2](https://github.com/user-attachments/assets/5fe3e434-3d9d-4491-9a69-ae3f30d078fe)
---
![blackjack3](https://github.com/user-attachments/assets/1d24789f-b1e8-44ca-9e45-528797a10693)
### Roulette

![roulette1](https://github.com/user-attachments/assets/ad33c1d0-f233-4d1f-9055-0facab3225b5)
---
![roulette2](https://github.com/user-attachments/assets/b8a97637-a138-4128-a9a3-21a9009bc856)
---
![roulette3](https://github.com/user-attachments/assets/95ae2472-6f3a-4812-8174-2ccda1838f1c)


