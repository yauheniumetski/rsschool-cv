# **EVGENY UMETSKI**

**Location**: Warsaw, Poland

**Phone**: +48 514 673 209

**Email**: umetskiiyauheni@gmail.com

**Linkedin**: [EVGENY UMETSKI](https://www.linkedin.com/in/evgeny-umetski)

**GitHub**: [@yauheniumetski](https://github.com/yauheniumetski)

---

### **Applying for a position of a QA Engineer.**

**Skills**

- API Testing
- TestRail
- Swagger
- Regression testing
- Postman
- Functional testing
- SQL
- DWH Testing
- Google Chrome Developer tools
- Jira
- Fiddler
- Test cases, test documentation
- GIT
- Test plan
- Datadog
- Automation test results analysis
- JavaScript
- Automation tests
- Microsoft Azure
- Selenium
- HTML5, CSS3
- NUnit/xUnit
- Playwright
- XPath, CSS locaors

**Languages**:

- **Russian Proficiency**: Native
- **English Proficiency**: B2
- **Polish Proficiency**: B1

## **Work experience**

![Amaryllis Payment Solutions](img\amaryllis-logo.png)

April 2022 – now: QA Engineer, [Amaryllis Payment Solutions](https://www.linkedin.com/company/amaryllis-payment-solutions).

April 2023 – now: manual testing 80% / automation tests 20% of work time – write automaton tests with .Net

**Project description**: Web-platform – Payment solution for Complex Payment Models (CPM).

**Responsibilities**: manual testing, web testing, API testing (Postman + JS), database testing, requirements testing, regression/smoke testing, cross-browser testing, log analysis, test documentation creation, defect validation.
Responsibilities also include new feature testing, defect validation, regression testing, designing and maintaining of test documentation, creation of quality reports, working with requirements, submitting issues, communicating with
the team, participating in project meetings.

---

![a1qa](img\a1qalogo.svg)

July 2021 – April 2022: QA Engineer (Functional tester), [a1qa](https://www.linkedin.com/company/a1qa).

**Project description**: Web-platform – Gambling platform. Testing games integrated with gambling platform.

**Responsibilities**: manual testing, web testing, API testing, mobile testing, database testing, requirements testing, regression/smoke testing, cross-browser testing, log analysis, test documentation creation, defect validation.
Responsibilities also include new feature testing, defect validation, regression testing, designing and maintaining of test documentation, creation of quality reports, working with requirements, submitting issues, communicating with the team, participating in project meetings.

March 2021 – June 2021: Trainee QA Engineer, [a1qa](https://www.linkedin.com/company/a1qa).

**Project description**: Web-platform – Platform for training.

**Responsibilities**: Test documentation creation and support, functional testing, reporting and analysis of the test results and product quality, GUI testing, exploratory testing, Communication with development team.

---

### **Education**

January 2024 - May 2024: [RedRover School](https://www.linkedin.com/company/redrover-school).
**Course**: Automation testing, Playwright + JS

**Code example:**

```JS
    for (const subCategory in MEN_PAGE_SUB_CATEGORY_ENDPOINT_URL) {
        test(`${subCategory} sub-category link led to the ${subCategory}-Men page`, async ({ page }) => {
            const homePage = new HomePage(page);
            const subCategoryPageEndpointUrl = MEN_PAGE_SUB_CATEGORY_ENDPOINT_URL[subCategory];

            const menPage = await homePage.clickMenLink();

            await expect(menPage.locators.getSubCategoryLink(subCategory)).toBeVisible();
            await menPage.clickSubCategoryLink(subCategory);

            await expect(page).toHaveTitle(`${subCategory} - Men`);
            await expect(page).toHaveURL(new RegExp(subCategoryPageEndpointUrl));
        });
    }
```

October 2020 - December 2024: Trainee QA Engineer, [Educational Center for Programming and High Tech IT-Academy](https://by.linkedin.com/company/educational-center-of-htp-it-academy-).
**Course**: Functional software testing

September 2015 – December 2016: [Belarusian National Technical University](https://bntu.by/en). **Specialization**: Construction. Master’s degree.

September 2008 – June 2014: [Belarusian National Technical University](https://bntu.by/en).
**Specialization**: Energetical construction. Construction engineer
