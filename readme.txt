This Metasploit module is for use with the "Arctic" Hack The Box machine - I did not write this module, I simply modified it slightly.

The original Metasploit module won't work on Arctic, as there is a massive amount of delay on this machine, so it just times out on upload (and then again when executing the reverse shell with the get request).

Simply rename the existing module (coldfusion_fckeditor.rb) located in /usr/share/metasploit-framework/modules/exploits/windows/http/coldfusion_fckeditor.rb

Then rename "coldfusion_fckeditor.rb_modified_by_xero" to "coldfusion_fckeditor.rb" and place it in the same directory.

You will need to restart Metasploit in order to reload the module properly using the new file.

Enjoy!
-X3R[]
