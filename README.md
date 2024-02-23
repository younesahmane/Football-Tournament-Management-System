# Football-Tournament-Management-System
## Abstract
The FTMS is designed for managing football tournaments, specifically tailored for the Algerian League 1 championship. It utilizes Binary Search Trees (BST) in Part A and AVL Trees in Part B for efficient data organization. The system covers game details, player statistics, team standings, and historical records, providing flexibility for different football championships.

## Introduction
FTMS addresses the specific needs of the Algerian League 1 championship, focusing on efficient data organization and analysis. Utilizing BST in Part A and AVL Trees in Part B ensures quick access to game outcomes, player performance, and historical records.

## DataSet
Teams in the Algerian Football League 1 in the season 2023/2024 are used, supplemented by additional Algerian teams. Player, coach, and president names are sourced from the official website, with some inventiveness due to data limitations. Games are generated using C++ functions and stored in a .txt file.

### Game Class
Represents each game between two teams.
Contains game details such as date, referee, duration, and score.
Tracks player statistics including entry time, replacement time, kilometers run, and cards received.
### Player Class
Represents soccer players and their statistics.
Uses an enumeration for player roles and a vector for storing goal statistics.
Provides setters, getters, and a function to print a bar chart of a player's goals.
### TeamEntity Class
Represents a player in a historical context.
Stores the total number of goals scored by the player historically.
### Team Class
Stores information about each team in the tournament.
Utilizes vectors for players, goals, points, and played games.
Includes methods for retrieving statistics up to a certain week and modifying the team roster.
### Tournament Class
Encapsulates essential components of a sports tournament.
Stores teams, players, and game details.
Uses a vector of weeks, each containing an AVL Tree of teams' points up to that week.
## Complexity Analysis
Compares running time performance of BST and AVL Trees for player ranking.
Recommends using AVL Trees for enhanced system efficiency.
### History Class
Stores all tournaments from the beginning.
Utilizes a vector for dynamic size and constant access time.
Includes functions for adding, displaying, and searching for tournaments.
## Console Interface
User-friendly interface with personalized greetings.
Menu-driven system for seamless navigation.
For more details, refer to the UML class diagram.

https://drive.google.com/drive/folders/1sSSyuUGVdDu0tOSGP2961AqsnBjKIoAR?usp=sharing
User-friendly interface with personalized greetings.
Menu-driven system for seamless navigation.
For more details, refer to the UML class diagram.

