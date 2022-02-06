# Rock, Paper, Scissors
Program the game Rock, Paper, Scissors such that you play against the CPU, who chooses values at
random. Play as many times as you like. Total games played and win count are tracked as long as
the program is running.

## Requirements
- The program is only required to work if the user input are numbers.
  - Error messages should be printed to the error stream using `std::cerr`.
- Paper beats rock, rock beats scissor, scissor beats paper.
- Keep a count of the player's wins and total games played.
  - Display these counts aftter every round; see the Sample Run.
- After each round, the menu is shown again for players to continue playing as long as they enter
a valid choice between rock, paper, or scissor.
- When displaying tallies, ensure that the message states "game" instead of "games" after the first
round; see the Sample Run.
- Possible outcomes:
  - You win
    - Display the message "You are victorious!"
    - Tottal game count **and** score increase by 1
  - You lose
    - Display the message "You lose."
    - Total game count increases by 1.
  - You tie
    - Display the message "It's a tie!"
    - Total game count increases by 1.

## Sample Run
```
*** Rock, Paper, Scissors ***
Choose your fate:
        1. Paper
        2. Scissor
        3. Rock
        #. Quit (any other number)

Enter the number of your choice: 1

You chose PAPER.
Your opponent chose ROCK.

You are victorious!
*** You have played 1 game.
*** Your total score is 1.

Choose your fate:
        1. Paper
        2. Scissor
        3. Rock
        #. Quit (any other number)

Enter the number of your choice: 2

You chose SCISSOR.
Your opponent chose ROCK.
You lose.

*** You have played 2 games.
*** Your total score is 1.

Choose your fate:
        1. Paper
        2. Scissor
        3. Rock
        #. Quit (any other number)

Enter the number of your choice: 5
Thanks for playing!
```

## Hints
- You do not need to test for all possibilities.
- The name of the game only appears once.
- Your choice of loop will have an observable impact on what your code looks like.
  - When deciding on a loop, it will benefit you to consider the different loops,
their viability, and what the differences might be.

## Reminders
- Name your file *wsuid*\_hwXX.cpp
- You are required to place a comment block at the top of the file. Refer to the Coding Guidelines
handout.
- Provide meaningful comments.
