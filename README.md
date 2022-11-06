## Venom-Wifi

<h3><p align="center">DISCLAIMER</p></h3>

Any action tor activity related to this tool is <b>your</b> sole responsibility. Misuse & abuse of this toolkit may result in criminal charges against the individuals in question. Contributors shall not be liable for your actions.


This tool is for educational purposes only. Do everyone a favor & don't be an a***ole. The world has enough of them already.

##

This is a script that automates obtaining the WPA handshake.  When a user connects to a wifi network, a 4-way handshake occurs.
This process transmits 4 messages in order to confirm that both the user and the router both have the correct credentials to start the communication (using the internet). 
This handshake can be used to crack the password by brute force. In addition, this script has the ability to knock down a wifi network with a Denial of Service attack, DoS. 
##

## Recommendation

Before starting, it is recommended you obtain a wall-penetrating wifi antenna. A popular one in the world of pentesting is ALPHA brand antennae or antennae with a Ralink chipset.

<p align="left">
	<img src="https://i.imgur.com/wE0eG8t.jpg" width="30%" height="30%">
</p>

### Installation

Clone the repository and change the permissions.

```markdown
git clone https://github.com/xeddmc/venom-wifi.git
cd venom-wifi
chmod +x venom-wifi.sh
sudo ./venom-wifi.sh
```

## Start

Select the option you prefer, you can choose between attacking the network directly or cracking the password by brute force using a dictionary attack.

<p align="left">
	<img src="https://i.imgur.com/PB6TxQ7.png" width="60%" height="60%" height="60%" align="">
</p>

## Obtain Handshake

On startup, a terminal window will open and gradually display the available wifi networks. Once you find a target, press Ctrl + C and close the window.
The list of available networks will appear, select the one you want and start the attack.

<p align="center">
	<img src="https://i.imgur.com/xPt2Psi.png" width="100%" height="100%" height="100%" align="">
</p>

## Results

Once the handshake is obtained, the program will automatically detect and save the .cap file in the 'captures' folder with the filename of the compromised network.
<p align="center">
	<img src="https://i.imgur.com/4xLFWjz.png" width="100%" height="100%" height="100%" align="">
</p>

## Password cracking

Choose from the default dictionary or select your own password dictionary to crack the password with brute-force.
<p align="center">
	<img src="https://i.imgur.com/HEQAWxi.png" width="100%" height="100%" height="100%" align="">
</p>

## DoS

Follow the same steps as in the last section, but switch to the "Knock down the network" option, it will automatically start the Dos attack on the selected wifi network.
To stop the attack press ctrl + C.


<p align="center">
	<img src="https://i.imgur.com/dStEmWc.png" width="100%" height="100%" height="100%" align="">
</p>
