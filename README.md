# DoctorAssig
Features
1. Appointment Booking Form
When a user clicks on "Book Appointment", a modal/popup or a new page opens with a form to collect appointment details.

Form Fields:

Patient Name (Input)
Age (Input)
Gender (Dropdown)
Mobile Number (Input)
Preferred Date (Date Picker)
Preferred Time Slot (Dropdown)
Submit Button: Saves the appointment details in the local state.
2. Appointments List Page
Displays a table/list of all booked appointments.

Each row shows:

Patient Name
Doctor Name
Date
Time
Edit Button: Allows editing of appointment details.
Cancel Button: Allows removal of an appointment.
Installation
1. Clone the Repository
First, clone the repository to your local machine:

git clone https://github.com/yakshitwadhwa/DoctorAssig.git

Then, navigate to the project folder:

cd DoctorAssig

2. Install Dependencies
Make sure you have Node.js and npm installed on your system. If you don’t have them yet, you can download and install them from here.

Once Node.js and npm are installed, run the following command to install the project dependencies:

npm install

3. Run the Project Locally
After installing the dependencies, start the development server with the following command:

npm run dev

This will start the development server, and the app will be available at:

http://localhost:5173/

You can open this URL in your browser to view the app.

How the Appointment System Works
1. Booking an Appointment
Click on "Book Appointment" to open the booking form.
Fill in the details like Patient Name, Age, Gender, Mobile Number, Preferred Date, and Preferred Time Slot.
Click Submit to save the appointment in the local state.
2. Viewing Appointments
The Appointments List Page displays a list of all the booked appointments in a table format.
Each row contains the patient's name, doctor's name, date, and time of the appointment.
3. Editing or Canceling an Appointment
Use the Edit button to modify the appointment details.
Use the Cancel button to remove the appointment from the list.
Technologies Used
React.js: For building the user interface.
Vite: A fast and modern build tool for development and bundling.
JavaScript: For functionality and logic.
CSS: For styling the app.