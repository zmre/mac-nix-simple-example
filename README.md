# Companion to Walkthrough of Nix Install and Setup on MacOS

This is a simple Nix MacOS flake and shows the progress and final state of the config used in the video [Walkthrough of Nix Install and Setup on MacOS](https://youtu.be/LE5JR4JcvMg).

Take a look at earlier commits to see what a really basic single file flake looks like with nix-darwin and home-manager.

## Video description

This is a live walkthrough of an install of Nix on a fresh MacOS system and a tutorial showing how to make a declarative config that will meet all of your needs on MacOS.

Steps:

1. Install of nix
2. Creation of basic flake
3. Addition of nix-darwin and home-manager
4. Initial bootstrap of config
5. Config enhancements showing linked config files and homebrew control
6. Demonstration of adding a remote flake as a package
7. Refactor of single nix file into multiple files and other simplifications

Nix example code:

* [Initial working flake](https://github.com/zmre/mac-nix-simple-example/blob/2c6465d9df0f42e279681e2c30eaf8ed998940be/flake.nix)
* [Embellished flake](https://github.com/zmre/mac-nix-simple-example/blob/502fbabcaaaf160081926498641a042995de19c2/flake.nix)
* [Final refactored version](https://github.com/zmre/mac-nix-simple-example)
