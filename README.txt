cs160_proj1
===========

OVERVIEW

	This assignment is a review of the basic tools of web interfaces: HTML, CSS, DOM, and Javascript. The goal is to implement the interface for a simple card game (you don't need to implement the game logic, just the ability to display and simply manipulate cards). You don't need to use any advanced features of HTML5 or CSS3, but you can if you want to - they will be needed for the optional features listed below. Your solution will ideally run on any browser, but we will be testing it on Google Chrome. Google Chrome, like Apple Safari, is based on the Webkit engine, which has the highest level of HTML5 compliance at this time. This will be important later in the semester.

INSTRUCTIONS

Main Display:
	Your main display should show five playing cards in a horizontal row, face up. Below the five cards should be a display of two piles (face down). One is the dealing pile while the other is a discard pile.
You don't need to implement all 13 cards in each suit. Just implement cards 2-6 for each of hearts, spades, clubs, and diamonds.

Behaviors:
	Clicking on one of the five cards should cause it to be removed to the discard pile - in the simplest implementation, this just means that the card disappears.
Clicking on the dealing pile should cause a new card to replace any empty space in the main row of five cards. If there are no empty spaces, a new card should replace a random card from among the five.
