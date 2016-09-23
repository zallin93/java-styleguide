# Java Style Guide

## Nobody Team Endorsed
So far, nobody has reviewed or contributed feeback, thus this style guide is my own. 

## Purpose
*Opinionated Java style guide for all users.*

This is the place where I tell you how to style your code, and you do it.  If you don't like it, then at least consider the points I suggest.  Too often do I see poor standards in enterprise-level Java code. 

The purpose of this guide is to show how I build my Java applications, and write my code so that it is easily read, understood, and then used by other programmers.  

If you like this guide, sweet.  If you don't, I'm still glad you read it. 

## Credit
I believe that credit should be given where credit is due.  If you provide me with input, I will do my best to credit you where appropriate. 

If you happen to use my guide, please feel free to let me know.  The more it is used, the more I will add and keep up with the latest "best practices."

## Sample Application
At some point in the future, I may add a sample application to this repository that shows a complete project with my styles implemented.  For now, this is what you get. 

## Table of Contents

 1. [General Style](#general-style)
 1. [Naming Conventions](#naming-conventions)
 1. [Comments](#comments)
 1. [Testing](#testing)

## General Style
When reading through an application's source code, I should not be able to tell how many developers have contributed.  Sometimes *@author* tags or the sheer size of an application might give this away, but by only reading the code, I should be ignorant.  The code base should be cohesive and make sense.  If it doesn't, you know what to do.  Refactor.  Refactor.  Refactor.  

## Naming Conventions
As originally a C developer, I am partial to **skeleton_casing**.  Using underscores makes quick reading and differentiating between similar class/method/variable names very easy.  Issues may arise when relying on 3rd-party libraries for automatic processing of your code.  

The original Java standard is to use **camelCasing**.  

The most important thing is to remain consistent.  Consistency should extend beyond a single method or class; your entire application should use consistent naming conventions.  


## Comments
Comments are the most useful text in any application.  Without them, no one would understand the spaghetti code you wrote when you were drinking last night. 

Even when I find myself 4 PBR's deep, I am able to relatively easily figure out what my code is doing if I have comments in my code. 

## Testing
Junit tests should be written for nearly all of your classes.  Your application is not a special snowflake; write the damn tests.  

Some situations may not call for Junit tests to be written.  One such case, might be if you are building a web service application.  In this case, you should instead be writing integration tests.  

Test your code.  Automate those tests.  [Just do it](https://giphy.com/gifs/shia-labeouf-just-do-it-wErJXg1tIgHXG).

