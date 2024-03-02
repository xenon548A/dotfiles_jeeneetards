# DOTFILES JEENEETards_UI project
### Before doing anything make sure to have a copy of the files you are removing/replacing, just in case some unexpected behaviour occurs.
--------------------------------------------------------
- How to add css to firefox?
  - Doing so is pretty easy, you have your firefox files located in `/home/user/.mozilla/firefox`,
    in the `/firefox` directory, go to the ```/pdko50mq.default-release/chrome/``` directory, and 
    replace the `userChrome.css` and `userContent.css` with my files, the bg-wallpaper should be in
    the very same `/chrome` directory. If you do not have a ```chrome``` folder or any of the mentioned 
    files, then just create them!
  - If the background does not change, then in the firefox search bar, put ```about:config```, 
    change ```toolkit.legacyUserProfileCustomizations.stylesheets``` to true,
    if it still does not change anything, then restart your computer (this worked for me).
- I have set the image names very weirdly, so change them to your preferences, however you want.
- For any customizations to this config's used applications, you can refer to the respective documentations 
  of the applications.
- My super/MOD key in i3 is `alt`, you change it to whatever you want.
- In the ```i3/scripts/``` directory, there is a script to hide/toggle the i3bar, named ```i3togglebar.sh```,
  it hides the i3bar on pressing `mod/super+h`, you can change this key upto your preferences.

> Terminal : Kitty
