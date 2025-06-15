

🩸 Blood Bank Management System – v1.0.0 Release

🔖 Tag: v1.0.0

📅 Release Date: 2025-06-15


---

🚀 Highlights of this Release

This is the initial public release (v1.0.0) of the Blood Bank Management System, a Django-powered web application designed to streamline blood donation, donor management, and hospital coordination.


---

🛠️ Key Features:

🔐 Admin Panel
Manage donors, blood groups, hospitals, and requests efficiently.

🧑‍💉 Donor Registration Module
Register new donors with name, age, blood group, contact info, and location.

🩸 Blood Group Availability Tracker
Real-time stock display for each blood group.

🏥 Hospital Request Handling
Hospitals can request required blood types with quantity and urgency.

🔍 Search Functionality
Find donors or blood groups using filters like city, blood group, or availability.

📧 Notification System (Basic Email)
Send email alerts to donors when blood is needed (can be extended with Twilio/SMTP).



---

⚙️ Tech Stack

Python 3.x

Django 4.x

SQLite3 (default) – can be migrated to PostgreSQL

HTML/CSS + Bootstrap for frontend

Optional: SendGrid/SMTP for email notification



---

✅ Setup Instructions

git clone https://github.com/yourusername/blood-bank-management.git
cd blood-bank-management
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Login to admin:
/admin → username: admin | password: admin@123


---

📌 Future Enhancements (Planned for v1.1.0)

SMS Notification Integration (Twilio)

Advanced Search and Filters

User Dashboard for Donors & Hospitals

PDF Report Generation



---

🙏 Contribution & Feedback

Feel free to report bugs or request features via Issues. Pull requests are welcome!


