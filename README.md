# PresenceOverflow
Modifies your Discord Rich Presence with a nice UI. <br/>
You can download the most recent version [here](https://github.com/woahoverflow/PresenceOverflow/releases/download/v0.2.0-ALPHA/PresenceOverflow-0.2.0-ALPHA.jar).

## Known Issues
+ Switching the name of the app in the Discord dashboard doesn't change it when reloading.
+ Sign in UI isn't the right size
+ Limited options for sign in (no register etc)
+ The end of the text options aren't the same (state, details etc)
+ Profiles are marked as green even though something's been altered
+ Signing in is basically useless (save configs on cloud)

## How to
To begin, head over to [here](https://discordapp.com/developers) and make sure you're signed in. After that, click on "New Application" on the dashboard. ![Dashboard](images/discord-dashboard.png "Dashboard")
After that, create a name. This name does matter towards your presence. It's the bold lettering at the top (see the bottom). Copy the "Client ID" from this dashboard.
![App Dashboard](images/app-dashboard.png "App Dashboard")
Once you've completed that, head back to your PresenceOverflow client. Put the Client ID into the client id section, and then insert a state. You only need a state, the others are optional. Once you've inserted what you want, click reload at the top right of the client. The "Unloaded" should turn into "Updated!".
You can now simply close it, and get it back by opening your toolbar full of icons on the far right of your taskbar.

## Troubleshooting
If it's for some reason not showing, and you've followed all of the steps, please try some of these. <br/>
**1**
![Game Activity](images/game-activity.png "Game Activity Panel")
Go into your Discord settings, go to Game Activity and enable "Display currently running game as a status message."
<br />
**2** <br />
Remove all of the information from Big Image Key, and Big Image Caption, Small Image Key, and Small Image Caption.

## How to add images
Make sure you've followed How To above before this. <br/>
Go back to your [Discord Developers Dashboard](https://discordapp.com/developers), and go to the Art Assets section.
![Image Dashboard](images/img-dashboard.png "Image Dashboard")
Go near the bottom, and click "Add Image(s)"
![Add Image](images/img-add.png "Add Image")
After that, upload an image and select a name.
Like it says, you cannot switch this name after.
![Upload Image](images/save-img.png "Upload Image")
The name you selected in the dashboard, is what you'll put in your PresenceOverflow client as either the big or small image key. Make sure to add a caption to that image size as well.

<br><br>
![Example Image](images/example.png "Example Image")<br>
If you hover over either of the images, the caption for that size would show.

## Disclaimer
This tutorial is intended for version(s) **v0.2.0-ALPHA**
