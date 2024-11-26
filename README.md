---
# Newspaper App 🌐

_A beginner-friendly Django project from the "Django for Beginners" book by William S. Vincent._

This project is a simple news website designed to teach the fundamentals of Django's Model-View-Template (MVT) architecture. It includes features like dynamic articles, a user-friendly admin interface, and clean templates.
---

## Features 🚀

- **Dynamic News Articles**: Add, edit, and manage news posts with a title, body, and timestamp.
- **Admin Panel**: Manage content with Django's built-in admin interface.
- **Clean Design**: Use Django templates to display articles and detail views.
- **Database Integration**: Store and retrieve data seamlessly using Django models.
- **Basic Testing**: Write tests to ensure functionality.

---

## Installation 🛠️

Follow these steps to get the project up and running locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/news-portal.git
   cd news-portal
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

6. Visit the app in your browser:  
   [http://localhost:8000](http://localhost:8000)

---

## Usage 📖

- **Admin Access**:  
  Create a superuser to access the admin panel:
  ```bash
  python manage.py createsuperuser
  ```
  Then log in at [http://localhost:8000/admin](http://localhost:8000/admin).
- **Adding Articles**:  
  Use the admin panel to add, edit, or delete news articles.

---

## Testing 🧪

Run the included tests to ensure the app works as expected:

```bash
python manage.py test
```

---

## Project Structure 📂

- **`news/`**: Main app for managing articles.
- **Templates**: HTML files for rendering views.
- **Models**: Database schema for articles.
- **Admin**: Interface for managing content.

---

## Learning Goals 🎓

- Understand Django's MVT architecture.
- Work with models, views, templates, and URL routing.
- Explore Django's admin interface and testing framework.

---

## Resources 📚

This project is based on the _Django for Beginners_ book by William S. Vincent. Check out the [official website](https://djangoforbeginners.com/) for more details.

---

## License 📄

This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if you'd like to include anything else, like screenshots or deployment steps!
