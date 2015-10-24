# MapTool Bundle
Support for the  [RPtools MapTool](http://rptools.net) macro language, plus embedded HTML.

![MapTool Bundle](http://i.imgur.com/drLANQp.png)

## Features
 * **Syntax Highlight**

Does recognize pretty much everything inside the macro tags (there’s some bugs with variables that does contain numbers, though)

 * **Code Completion**

It just completes anything you’re typing, and cycles through options (Macromates needs to implement a way to show a list of options)

 * **HTML Markup Highlight**

I’ve used the built-in HTML bundle from Macromates, so it doesn’t highlight macros inside HTML, like macros for in href attributes (maybe will support in a future version)

 * **Supports dragging .mtmacro files, loading the macro contents**

Oh, just a small props. if you drag a .mtmacro file on TextMate, it will get the macro contents and put into the text area. You’ll have to select the file type to activate the highlight, as I haven’t found a way to set that

## Grab your copy
 * [Releases page](https://github.com/wwmoraes/MapTool.tmbundle/releases)
 * [Master branch zip](https://github.com/wwmoraes/MapTool.tmbundle/archive/master.zip)
  * Unzip and add `.tmbundle` to the end of the folder name

## How to install
Drop the .tmbundle file in the `~/Library/Application Support/Avian/Bundles` directory (you can use Shift+Cmd+G and paste this path to go straight to it!), then open TextMate.

Also, AFAIK this bundle is supported by other editors, like Sublime Text, e-TextEditor and probably others that states to be "TextMate-compatible".

## To-Do’s

 * Fix variable regex to match names with numbers aside commas (LOL)
 * Highlight macro commands inside HTML strings (e.g. href attributes)
 * Add drop support for other file types (rptok, rpcpmn, etc)
 * Automatically set the syntax type on drops

Happy macro’ing!