<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The keypad rows are scanned one by one, and their state is
stored into a local 16-bit register. Each bit in this register
corresponds to one key on the keypad.

The output of the 16-bit register is then converted to the 
7-segment display with some simple combinatorial logic.

There are no debouncing, latching or some other advanced
features.

## How to test

Connect a keypad, reset, and start pressing the keypad keys.
Corresponding numbers, and character should be shown on the 
7-segment display.

## External hardware

Keypad matrix 4x4
