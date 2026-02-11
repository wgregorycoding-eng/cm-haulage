# CM Haulage LTD - Logistics & Courier Website

## UX 

### 1. Project Goals
The primary goal of the **CM Haulage LTD** website is to provide a seamless, professional, and trustworthy interface for businesses and individuals to manage their logistics needs.

#### **User Goals**
* **Efficiency:** Quickly book a courier or request an urgent quote for same-day or next-day delivery to keep business operations moving without delay.
* **Transparency:** Access clear information regarding nationwide UK coverage and the range of clean, modern vehicles available, from small vans to larger trucks.
* **Trust:** Verify company legitimacy through professional branding and a reputation built on the three key principles of punctuality, communication, and care.
* **Service Clarity:** Easily identify specific logistics solutions including pallet distribution, contract haulage, multi-drop deliveries, and dedicated vehicle services.
* **Reliability:** Gain peace of mind knowing all goods are treated with the highest level of professionalism, secured correctly, and handled with extreme care from collection to delivery.

#### **Business Goals**
* **Lead Generation:** Convert site visitors into active clients via high-visibility "Request a Quote" forms for diverse sectors such as construction, retail, and manufacturing.
* **Brand Authority:** Establish CM Haulage Ltd as a premier logistics provider in the South Yorkshire region through a clean, modern, and trustworthy digital presence.
* **Strategic Positioning:** Emphasize the competitive advantage of the Sheffield base, which allows for immediate access to major motorway networks for efficient national reach.
* **Partnership Growth:** Promote long-term contract haulage opportunities for businesses requiring regular, dependable transport support and dedicated driver services.
* **Operational Excellence:** Highlight the commitment to safety and reliability by showcasing a fleet that is regularly inspected, serviced, and maintained to the highest standards.

The development of this website is based on the official information sheet provided by **CM Haulage LTD**. This document outlines the company’s core values, service specifications, and operational requirements.

* **Project Brief:** [View Information Sheet](assets/CM_Haulage_Website_Info.docx)
* **Key Requirements derived from the sheet:**
    * Adherence to corporate branding (Navy/Yellow).
    * Integration of specific fleet details (HGVs and Vans).
    * Focus on nationwide UK coverage.

#### **User Stories**
| As a... | I want to... | So that I can... |
| :--- | :--- | :--- |
| **New Customer** | Easily find the "Get a Quote" button and transparent pricing | I can budget for my nationwide shipping costs quickly and without hidden fees. |
| **Business Owner** | View the specific range of clean, modern vehicles (from vans to trucks) | I can ensure my specialized cargo (e.g., construction or retail supplies) can be handled safely. |
| **Returning Client** | Access clear contact details and communication channels | I can get professional, punctual updates on my ongoing delivery or long-term contract work. |
| **Operations Manager** | Find information on pallet distribution and multi-drop delivery services | I can coordinate complex logistics for my warehouse or distribution center efficiently. |
| **Urgent Sender** | Identify Same Day and Next Day delivery options immediately | I can keep my business moving without delay by booking a fast-response courier from the Sheffield hub. |

#### **Design Choices**
#### **Brand Identity**
* **Official Logo:** The logo used in this project was provided by **CM Haulage LTD** to ensure brand consistency. It is stored in the `assets/images/![CM Haulage Logo](assets/images/VTOS3354.JPG) 

#### **Color Scheme**
* **Primary Navy (#1A2B48):** Used for headers and stability.
* **Vibrant Yellow (#FDEE00):** Used for Action buttons (CTAs).
* **Metallic Silver (#C0C0C2):** Mimics the industrial feel of transport.

#### **Typography**
* **Primary Font:** Bold Sans-Serif (*Montserrat*) for headings.
* **Secondary Font:** Legible Sans-Serif (*Roboto*) for body text.

#### **Images & Icons**
* **Hero Image:** High-quality photography of heavy-duty vehicles (HGVs) and courier vans to immediately communicate the scale of operation.
* **Iconography:** Linear, minimalist icons representing **"Fast Delivery,"** **"Secure Handling,"** and **"Nationwide Coverage"** to break up text-heavy sections.

#### **Wireframes**
* **Mobile Wireframes:** ![Mobile Wireframe](assets/documentation/wireframes/mobile-design.png)
* **Tablet Wireframes:** ![Tablet Wireframe](assets/documentation/wireframes/tablet-design.png)
* **Desktop Wireframes:** ![Desktop Wireframe](assets/documentation/wireframes/desktop-design.png)

### 2. Information Architecture & Technical Implementation

This project is a multi-page static front-end application built to satisfy all mandatory technical specifications. The site is structured into five distinct pages, each utilizing a consistent **Bootstrap 5** navigation menu and custom **CSS3** styling to reflect the corporate Navy and Yellow brand identity.

#### **Site Structure**
1.  **Home Page:** Provides a high-level overview of CM Haulage Ltd as a Sheffield-based industry leader, introducing the core values of punctuality, communication, and care.
2.  **Services Page:** A detailed catalog of logistics solutions, including General Haulage, Same Day Delivery, and Pallet Distribution for industries like construction and retail.
3.  **Our Fleet Page:** Showcases the range of modern vehicles and emphasizes high maintenance standards and safety protocols.
4.  **Booking & Enquiry Page:** A functional area featuring a structured **HTML5** form for lead generation and transparent pricing requests.
5. **Success Page (Confirmation):**
    * **Purpose:** Provides immediate feedback after a form submission.
    * **Content:** A "Thank You" message confirming the enquiry was received, a summary of expected response times (e.g., "We will contact you shortly"), and a button to return to the Home page.

**Footer (On all pages):** Contact details, and **Social Media Links** (e.g., Facebook, X, Instgram) for brand transparency.

#### **Development & Standards**
* **Structured Layout:** Implemented using the **Bootstrap 5** framework to ensure a mobile-first, responsive user experience across all devices.
* **Version Control:** Developed using **Git** with a complete history of meaningful commits hosted on **GitHub**.
* **Deployment:** Publicly hosted via **GitHub Pages** for live accessibility.
* **Attribution:** Clear separation is maintained between custom code and external libraries (Bootstrap, Font Awesome, Google Fonts), with full credits provided in code comments and the Credits section below.

### Features
* **Responsive Design:** Fully functional and optimized for mobile, tablet, and desktop using a Bootstrap 5 grid system.
* **Booking Form:** A structured, multi-field form that captures essential logistics data, including load specifications, pallet counts, and nationwide routing details.
* **Enquiry Form:** A streamlined contact method for general business inquiries, contract haulage partnerships, and bespoke logistics advice.
* **Urgency Handling:** Dedicated high-priority fields for 'Same Day' and 'Next Day' requests to support fast-response business needs.
* **Fleet Gallery:** High-quality imagery and specifications of the haulage fleet, ranging from small vans to HGVs.
* **Trust Indicators:** Prominent integration of the 'Three Principles' (Punctuality, Communication, Care) and professional social media links in the footer to provide social proof.
* **Data Validation:** Built-in HTML5 validation to ensure all collection/delivery postcodes and contact details are accurate before submission.
* **Success Feedback:** A dedicated confirmation page that triggers upon successful form submission to reassure the user that their request is being processed by the Sheffield team.
#### **Features Left to Implement**

In future updates, I plan to include:
* **Live Tracking:** A real-time map for customers to track their haulage.
* **Customer Dashboard:** For returning clients to view their order history and provide feedback.
* **Automated Quoting Engine:** To provide instant pricing based on weight and distance.

### 3. Technologies Used
To build a robust platform for **CM Haulage LTD**, the following technologies were utilized:

* **HTML5 & CSS3:** For semantic structure and custom styling.
* **Figma** For wireframe designs in multiple sizes.
* **[Bootstrap 5](https://getbootstrap.com/):** Used as the primary CSS framework for a responsive, mobile-first layout.
* **[Font Awesome](https://fontawesome.com/):** For high-quality, scalable icons 
* **[Google Fonts](https://fonts.google.com/):** To import the *Montserrat* and *Roboto* typefaces for a professional look.
* **VS Code:** The primary Integrated Development Environment (IDE) used for coding.
* **[Autoprefixer](https://autoprefixer.github.io/)** adds vendor prefixes

### 4. Testing
To ensure a high-quality user experience and technical stability, the project underwent a rigorous testing phase using three primary methods:

#### **Manual Testing**
* **Navigation:** Verified that the persistent Bootstrap navigation menu functions correctly across all 5 pages.
* **Forms:** Tested the Booking and Enquiry forms to ensure required fields prevent empty submissions and that the "Success Page" triggers correctly.
* **Link Integrity:** Checked all external links (Social Media) and internal buttons to ensure they point to the correct destinations.
* **Responsiveness:** Manually inspected the site on multiple screen sizes (Mobile, Tablet, Desktop) using Chrome DevTools to ensure the grid layout remains professional.

#### **Automated Testing**
* **W3C HTML Validator:** All pages were processed through the [W3C Markup Validation Service](https://validator.w3.org/) to ensure semantic correctness and HTML5 compliance.
* **W3C CSS Validator:** The custom stylesheet was verified using the [CSS Validation Service](https://jigsaw.w3.org/css-validator/) to ensure no syntax errors were present in the branding implementation.
* **Lighthouse:** Ran Google Lighthouse audits to optimize performance, accessibility, and SEO.
    * **Performance:** Checked image optimization for the Fleet Gallery.
    * **Accessibility:** Ensured high color contrast between the Navy (#1A2B48) and Yellow (#FDEE00) branding for readability.


### 5. Deployment
The project was deployed to GitHub Pages using the following steps:
1.  Initialize the local directory as a Git repository.
2.  Commit all HTML, CSS, and asset files.
3.  Push the code to a public GitHub repository.
4.  Navigate to **Settings > Pages** in the GitHub repository and select the `main` branch as the deployment source.
5.  **Live Site Link:** [Insert GitHub Pages URL Here]

### 6. Credit
* **Brand Assets:** Logo and professional website copy provided by **CM Haulage LTD**.
* **Frameworks:** [Bootstrap 5](https://getbootstrap.com/) for layout and navigation.
* **Icons:** [Font Awesome](https://fontawesome.com/) for logistics and contact iconography.
* **Fonts:** [Google Fonts](https://fonts.google.com/) for *Montserrat* and *Roboto*.
* **Custom Code:** All HTML5 structure and CSS3 styling (including the Navy and Yellow brand implementation) was written by **[William Gregory]**.
* **Content:** Website copy and project brief provided by **CM Haulage LTD**.
