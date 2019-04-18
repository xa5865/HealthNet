Hello,
Welcome to HealthNet

System Requirements
Django 1.9.1
Python 3.4.3

Here are some instructions on how to startup HealthNet

1. Move the HealthNet folder to where you want to run the server from.
2. Hold SHIFT and rightclick on the folder.
3. Select "Open Command Window Here"
4. When the CMD terminal opens, run the commane "python manage.py runserver"
5. Go to localhost:8000/accounts/ to access the main page of HealthNet
6. Youre in!

Missing R2 features include:
-No System Stats
-No Exporting Patient Info
-Transfering a Patient implemented differently.


Note:
There are already some users registered on this site. This is done for the convinience of testing. Most, but not all, functions within HealthNet are hospital dependent. To make it easier to test, all users have either 'H1' or 'H2' at the end of their usernames. This is to determine which hospital (Hospital_1 or Hospital_2) they are in.

HealthNet Admins: 
These admins are admins for their appropriate hospitals.
 (They are also django admins, but that is only for convinience/testing)

UserName	Password
Admin_H1	password123
Admin_H2	password123

HealthNet Doctors:
UserName	Password
Doctor1_H1	pass123
Doctor2_H1	pass123
Doctor1_H2	pass123
Doctor2_H2	pass123

HealthNet Nurses:
UserName	Password
Nurse1_H1	pass123
Nurse2_H1	pass123
Nurse1_H2	pass123
Nurse2_H2	pass123


HealthNet Patients:
UserName	Password
Patient1_H1	pass123
Patient2_H1	pass123
Patient3_H1	pass123
Patient1_H2	pass123
Patient2_H2	pass123
Patient3_H2	pass123





