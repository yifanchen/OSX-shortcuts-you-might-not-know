# macOS Shortcuts Collection

I like shortcuts, and I hope you do as well. Feel free to create a PR and share your shortcuts. I have also written an <a href="https://github.com/yifanchen/advanced-keymapping">Advanced Keymapping</a> post, check it out if you want to take shortcuts to the next level.

## Editing

`cmd` + `left` or `right`: navigating through beginning and end of a line.

`cmd` + `shift` + `left` or `right`: select entire line.

`cmd` + `top` or `bottom`: top or bottom of the file

`cmd` + `shift` + `top` or `bottom`: select entire file from either top or bottom.

`cmd` + `del`: delete content behind cursor on the same line.

`alt` + `left` or `right`: navigating through word by word.

`alt` + `shift` + `left` or `right`: select word.

`alt` + `del`: delete the entire word, no long need to copy from other places.

`alt` + `8`: bullet.

`fn` + `delete`: forward delete.

`alt` + `shift` + `k`: 

The following shortctus are the inheritance from Unix. They work similarly as arrow keys when editing, but not the same when not editing. I only use them in Shell and Vim because I treat them as replacement of my `ctrl` + `hjkl` keybinding since I intentionally disabled them in iTerm for better Vim experience. Part of the reason that they are working is that arguably macOS took some concepts from Unix, so these shortcuts were inherited.

`ctrl` + `a`: go to beginning of the line when editing.

`ctrl` + `e`: go to end of the line when editing.

`ctrl` + `n`: go up when editing, i.e. selecting in intellisense.

`ctrl` + `p`: go down when editing, i.e. selecting in intellisense.

## System

`control` + `shift` + `power`: shorter to sleep, longer to shut down.

`cmd` + `~`: cycle through different windows in the current application.(one of my favorite OSX shortcuts, doesn't exist in Windows)

`cmd` + `,`: open preference of any application.

`cmd` + `l`: select address bar in any browser.

`cmd` + `w`: close application tab.

`cmd` + `shift` + `w`: close all tabs, but application is still running.

`cmd` + `q`: completely quit the application.

## Chrome

`control` + `tab` or `control` + `shift` + `tab`: navigating through tabs.

`cmd` + `shift` + `b`: toggle bookmark bar.

`cmd` + `shift` + `c`: inspect element ready.

`cmd` + `alt` + `i`: open developer tool without inspect element ready.

`cmd` + `alt` + `j`: open console window.

`cmd` + `alt` + `u`: open source.

`cmd` + `shift` + `d`: toggle dock side.

`cmd` + `shift` + `m`: toggle device view

`cmd` + `k`: clear console.

`cmd` + `left`: previous page.

`cmd` + `right`: next page.

`F2`: Edit as HTML in Chrome developer tool.

## Finder

`cmd` + `alt` + `l`: downloads.

`cmd` + `shift` + `h`: home.

`cmd` + `shirt` + `o`: documents.

`cmd` + `shirt` + `d`: desktop.

## Apple Mail && Exchange Mail

`control` + `p`: work same as `up arrow`, but not consectively.

`control` + `n`: work same as `down arrow`, but not consectively.

## Shell && Bash && Zsh && Command Line && Terminal

`control` + `z`: puts whatever you are running into a suspended background process. `fg` restores it.

`control` + `t`: swap the last two characters before the cursor

`control` + `w`: delete a word before the cursor.

`control` + `u`: delete entire line.

`control` + `k`: deletes the line from the position of the cursor to the end of the line.

`control` + `r`: search your command history

`control` + `a`: go to the beginning of the line.

`control` + `e`: go to the end of the line.

`control` + `h`: delete, same as `delete`.

`control` + `p`: previous command.

`control` + `n`: next command.

`control` + `l`: clear the screen.

`control` + `d`: end of file, works in Shell when wants to exit out an environment.

`control` + `c`: kill whatever you are running.

## Bash && Zsh Commands

There are hundreds commands in Bash, I am going to collect the ones we need to use daily.

`-`: go to the previous directory.(very useful)

`up` or `down`: previous and next command.

`pushd`: save current working directory to stack.

`popd`: grab saved directory from stack.

`dirs -c`: clean directory stack.

`pwd|pbcopy`: copy current working dir to clipboard

`pbpaste`: paste working dir from clipboard

`export`: setting environment variables.
