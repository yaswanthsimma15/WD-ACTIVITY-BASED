# 📚 BookNest — Digital Library

BookNest is a responsive digital library website interface built with **HTML5 and CSS3**. It helps users explore book categories, view featured books, check sample availability statuses, and browse a structured book catalog.

## ✨ Features

- **Responsive navigation** with links to the main sections.
- **Hero section** introducing the digital library and showing sample library statistics.
- **Search and filter interface** with fields for title/author keywords, category, availability, and sorting.
- **Book categories** for programming, artificial intelligence, science, literature, business, and self-development.
- **Featured book cards** with decorative covers, author information, descriptions, book IDs, and sample availability labels.
- **Catalog table** showing book ID, title, author, category, year, and status.
- **Library rules** presented as information cards.
- **Membership banner** encouraging users to explore the collection.
- **Footer** with quick links and library information.
- **Responsive layouts** for desktop, tablet, and mobile screens.
- **Accessibility considerations**, including semantic HTML, form labels, visible keyboard-focus styles, and reduced-motion support.

## 🛠️ Technologies Used

- **HTML5** — page structure and semantic content.
- **CSS3** — layout, colors, typography, gradients, hover effects, CSS Grid, Flexbox, and media queries.

## 📁 Project Structure

Keep the HTML and CSS files in the same folder:

```text
BookNest/
├── index.html
├── digital.css
└── README.md
```

> The HTML file links to the stylesheet using `href="digital.css"`. Make sure the CSS file has this exact name, or update the link in the HTML.

## 🚀 How to Run

1. Create a project folder named `BookNest`.
2. Save the HTML code as `index.html`.
3. Save the CSS code as `digital.css`.
4. Make sure both files are in the same folder.
5. Open `index.html` in a web browser.
6. Optional: open the folder in Visual Studio Code and use a local preview extension.

## 📚 Sample Catalog

The page includes six sample book entries:

| Book ID | Title | Category | Sample Status |
|---|---|---|---|
| BK001 | Python Programming | Programming | Available |
| BK002 | Artificial Intelligence | AI | Borrowed |
| BK003 | The World of Science | Science | Available |
| BK004 | Great Literature | Literature | Available |
| BK005 | Business Strategy | Business | Borrowed |
| BK006 | Personal Growth | Self-Development | Available |

Some titles and author details are illustrative sample content. Check the HTML before treating them as verified bibliographic records.

## ⚠️ Current Limitations

- The search box and filter controls are **interface elements only**. The HTML form does not implement live filtering or sorting.
- Book availability labels are static examples and do not update automatically.
- There is no database, login system, borrowing workflow, or backend integration.
- The displayed library statistics are sample values.

JavaScript and/or a backend would be needed to implement dynamic search, filtering, book records, member accounts, and borrowing functionality.

## 🔮 Possible Future Improvements

- Add JavaScript-based search, filtering, and sorting.
- Connect a database to manage books and availability.
- Add user registration, login, and member profiles.
- Implement borrowing, returns, due dates, and reservation features.
- Add real book-cover images and verified book metadata.
- Create an admin page for managing catalog records.

## 👨‍💻 Project Information

- **Project:** BookNest Digital Library
- **Type:** Front-end web development project
- **Built with:** HTML5 and CSS3
- **Author:** Yaswanth Simma

## 📄 License

This project is intended for learning and demonstration. Add a license file if you want to specify formal reuse and distribution terms.
