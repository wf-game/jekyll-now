# @Ubisoft

Today we presented our 5 - 10 min level of warp runners (previously warp fighters) to some members of Ubisoft. They provided a lot of 
valuable feedback that we can use to improve our game.


# Mechanics

The most important aspect is that we need to currently focus on is our camera and how it interacts with the world. They recommended us to
switch to a raycast implementation with the camera instead of using a physical collider to detect collisions in the world. The camera should
also be able to revolve around the character rather be clamped into place behind the character.

Adding on to that we definitely need to focus on making the mechanics feel good, and the camera is only one aspect of it. Other aspects
include changing our lock on system so that it will lock to nearest object rather than being near an object. We also need to implement air 
control as a large portion of the time the player will be in the air. There are also many other mechanics to fix such as make the launch pad 
only launch the player when he shoots himself at, change the buttons to a pad so player can walk over it without jumping, and etc ...


# Level Design

As for level design, right now it feels like there is no goal to the game, there maybe should be a better indicator of what exactly the player
should be aiming to achieve. We need to slowly introduce the players to the warp concept and what it is capable of, should be able to convey to
the player when you should warp and when you shouldn't. Currently , the enemies are placed randomly throughout the level and really gives no 
addition to the puzzles, they should be placed strategically to make the level more challenging for the player.


# Art

Well, we can't just leave the entire level gray-boxed, there should definitely be textures added to make the game nicer. They also suggested to 
add different particle effects for visual feedback when the character collides or destroys enemies. We definitely need to have a player model
and it should be animated and textured. We also have a lot of lighting issues in the level where shadows aren't being properly generated and
that needs to be fixed. 



