# custom-editfield

***Note: This is the official version since 2015. The code at code.google.com/p/custom-editfield is outdated.***

*CustomEditField* is a set of classes that are primarily designed to display source code and similar structured text, such as XML. It is ideal to show and edit Xojo / REALbasic (RbScript) code, for instance.

It comes with examples for performing a "diff" on two adjacent texts, and for using its syntax highlighting engine with other types of edit fields.

***Caution:*** When using this code in a ***Mac Cocoa*** app, text input with dead keys (e.g. by first pressing the ^ key, then a vovel key) will not work. To fix this, this code would need to use Xojo's TextInputCanvas plugin (https://github.com/xojo/TextInputCanvas), which it currently doesn't do.

Note: If you need a more complete word processing solution that provides several different editor types then check out the ***Formatted Text Control*** (http://www.bkeeney.com/formatted-text-control) from BKeeney Software Inc.

Supports all Xojo versions as well as REAL Studio 2012r2.1 (that's what Thomas Tempelmann uses for development).

###Installation

Open the project in the IDE, select the **CustomEditField folder** in the project and use the ***Copy*** command to copy the data to the clipboard. Then paste it into your own project. (Attention: If you're using Xojo, save your project first, close the project and re-open it, otherwise the control won't work, e.g. typing won't appear.)

To use it, drag the CustomEditField control into a Window.

###Features
 * Syntax Highlighting
 * Line auto-indenting (some problems, see Issues tracker)
 * Autocomplete
 * Line numbering
 * Invisible characters
 * Undo
 * Line Foldings (currently not fully working, see Issues tracker)
 * Find/Replace
 * Printing
 * Bookmarks
 * Placeholders

The project runs as a demo, showing off many of its features:

![cef-demo](https://cloud.githubusercontent.com/assets/461920/7630988/929d2024-fa3c-11e4-82bb-c78ba6242609.png)
