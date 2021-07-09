This is a mudlet package to track items you've stored across inns within WoTMUD. Functionality is quite simple:

you logon and automatically trigger a "score" which is required to capture your characters name. If you then perform a list action at an inn the script will capture all stored items in that inn, and save it in a sql database (stored in your mudlet directory). If you deposit/withdraw something at an inn, the trigger will perform a new list command to get the latest stored items at said inn. These are again stored in the database.

Finally you have one alias command to locate items/see what is stored where.

inndb help --> shows a brief help
inndb char --> shows all items stored for your character
inndb zone xxx --> shows all items stored in zone xxx
inndb item xxx --> searches for the item and shows in what inn/zone it's stored
inndb inn xxx --> shows all items stored at a specific inn.

Download the .mpackage file and import it within mudlet.
