# BuyNPC Script

This script automates the process of buying items from NPCs in the game. It uses the Windower API for Final Fantasy XI to interact with the game. This script focuses on purchases made where a menu selection needs to occur before making the purchase (conquest npcs, sparks, etc). Menu based purchases work with in game points like Sparks/Accolades/Conquest Points/Imperial standing. So make sure you have enough before proceeding with the transaction.

## Features

- Buy multiple items at once
- Buy items multiple times until inventory is full
- Stop the current operation
- Reload the script without restarting the game

## Usage

To make a purchase you must know the NPC name (casing not sensitive), and the name of the item you wish to purchase from that npc. e.g.

``` //buy "crying wind, i.m." "musketeer gun" 10```

This command will buy 10 guns as long as its available, and you have enough imperial standing to purchase all 10. 

If you wish to purchase until your inventory is full you can use the following command:

``` //buy "crying wind, i.m." "musketeer gun" full```

To stop the current operation at any time, run:

``` //buy stop ```

To reload the script, use the following command:

``` //buy r ```

This command will reload the script. This is useful if you've made changes to the script and want to apply them without restarting the game.