
<html>
    <head>
        <title>Logika School</title>
    </head>

    <body>

    <header>
        <img src="https://static.tildacdn.one/tild3030-3164-4261-a362-386432353161/Group_1.svg"  alt="logo" />
        <nav>
            <a href="#about">ПРО НАС</a>
            <a href="#catalog">КУРСИ</a>
            <a href="#principles">ІНШЕ</a>
            <a href="#signup">РЕЄСТРАЦІЯ</a>
            <a href="#contacts" class="nav-contact">КОНТАКТИ</a>
        </nav>
    </header>

    <main>
        <h1>LOGIKA SCHOOL</h1>
        <section class="about" id="about">
    <h3>Про нашу школу</h3>
    <p>
        Logika School — це сучасна IT-школа для дітей та підлітків, яка допомагає молодому поколінню здобути знання, необхідні в цифровому світі. 
        Ми викладаємо програмування, робототехніку, створення ігор, 3D-моделювання, дизайн, логіку та багато іншого.
    </p>
    <p>
        Наші курси розроблені для дітей віком від 6 до 17 років. Програми навчання адаптовані під різні вікові категорії та навички.
        Уроки проходять у зручному форматі: як онлайн, так і в наших сучасних офісах. 
    </p>

    <ul>
        <li> Сучасні методики викладання</li>
        <li> Індивідуальний підхід до кожного</li>
        <li> Маленькі групи для комфортного навчання</li>
        <li> Підтримка батьків: звіти, консультації, демо-уроки</li>
    </ul>
</section>
        <img class="head_img" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0vmuLcQitTGCLflcPsCZR2vXpLcnJV6gFxQ&s" alt="banner" />
        <p class="slogan_text">Навчайся сучасному — змінюй майбутнє вже сьогодні!</p>
        <h2 id="catalog">КУРСИ</h2>
        <section class="catalog">
            <article class="product">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeAKrj6jZ-bB4LX7q0FvVJOP22cNDUTwPhrOA2UBytWu-RNQmVepA0JG1W_9kPNqvBesk&usqp=CAU" />
            </article>
            <article class="product">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTnV-kJZNJhLqL-sZ0fuVlgsVCRZ5a1tD7hPQCCnHIrXkLQOwJd3Qyikd94wbf5Cz5R2tE&usqp=CAU" />
            </article>
            <article class="product">
                <img src="https://optim.tildacdn.one/tild3961-3730-4162-a339-306662333563/-/resize/260x/-/format/webp/Group_82.png.webp"  />
            </article>
            <article class="product">
                <img src="https://optim.tildacdn.one/tild6132-3763-4464-b938-313433646535/-/resize/260x/-/format/webp/Group_83.png.webp"/>
            </article>
            <article class="product">
                <img src="https://optim.tildacdn.one/tild3562-3737-4230-a665-333263383964/-/resize/260x/-/format/webp/Group_84.png.webp" />
            </article>
            <article class="product">
                <img src="https://optim.tildacdn.one/tild3364-6335-4462-b362-343362386364/-/resize/262x/-/format/webp/noroot.png.webp"  />
            </article>
        </section>
        <h2 id="principles">ІНШЕ</h2>
        <section class="principles">
            <article class="principle">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Flag_of_Ukraine.svg/500px-Flag_of_Ukraine.svg.png"  alt="Флаг України" />
                <p>НАЙПОПУЛЯРНІША IT-ШКОЛА В УКРАЇНІ</p>
            </article>
            <article class="principle">
                <img src="https://simona-life.com.ua/image/cache/catalog/image/cache/catalog/122132343245-519x367.webp"  alt="Перший урок у подарунок" />
                <p>ПЕРШИЙ УРОК У ПОДАРУНОК</p>
            </article>
            <article class="principle">
                <img src="/uploads/2021/02/icons-1831923_640_0_1612518875.png" alt="Завжди можна зв’язатися" />
                <p>ЗАВЖДИ МОЖНА ЗВ’ЯЗАТИСЯ</p>
            </article>
        </section>
        <section id="signup">
            <button class="signup-button" disabled>ЗАРЕЄСТРУВАТИСЯ</button>
            <p class="signup-note">Реєстрація буде доступна з 30.06.2025</p>
        </section>
    </main>

    <footer id="contacts">
        <h3>Контакти</h3>
        <p><strong>Електронна пошта:</strong> artemlogikal@gmail.com</p>
        <p><strong>Адреса :</strong> м. Кривий Ріг, вул. Ноутбукавська</p>
        <p><strong>Графік роботи:</strong> Пн–Пт, з 10:00 до 19:00</p>
        <button class="call-button" disabled>Подзвонити</button>
        <p class="call-note">Функція недоступна</p>
    </footer>

    </body>

</html>


body {
    font-family:  sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
    color: #333;
}


header {
    background-color: white;
    padding: 20px;
    border-bottom: 2px solid #eee;
    text-align: center;
    top: 0;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

nav {
    margin-top: 10px;
}

nav a {
    text-decoration: none;
    color: #531092;
    font-weight: 600;
    margin: 0 15px;
    transition: all 0.3s ease;
    font-size: 16px;
    padding: 8px 12px;
}

nav a:hover {
    color: white;
    background-color: #531092;
    border-radius: 20px;
}


h1 {
    text-align: center;
    margin: 40px 0 20px;
    font-size: 42px;
    color: #531092;
}

h2 {
    text-align: center;
    margin: 60px 0 20px;
    font-size: 32px;
    color: #531092;
}

.about h3 {
    text-align: center;
    margin-bottom: 35px;
    font-size: 24px;
    color: #531092;
}


.about {
    background-color: white;
    margin: 30px auto;
    padding: 25px;
    max-width: 900px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    line-height: 1.8;
    text-align: justify;
}


.head_img {
    display: block;
    width: 80%;
    margin: 30px auto;
    border-radius: 12px;
    box-shadow: 0 3px 12px rgba(0, 0, 0, 0.1);
}

.slogan_text {
    text-align: center;
    font-size: 20px;
    color: #666;
    margin-bottom: 40px;
    font-style:normal;
}

.principles {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 24px;
    padding: 20px;
}

.catalog {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 24px;
    padding: 20px;
}

.principle {
    background-color: white;
    padding: 20px;
    width: 30%;
    text-align: center;
    border: 1px solid #ddd;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product {
    background-color: white;
    padding: 20px;
    width: 280px;
    text-align: center;
    border: 1px solid #ddd;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product:hover, .principle:hover {
    transform:scale(100px);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.08);
}

.product:hover, .principle:hover {
    transform:scale(100px);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.08);
}

.catalog .product img {
    width: 50%;  
    height: auto;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.principle img {
    width: 60%;
    border-radius: 8px;
}

#signup {
    text-align: center;
    margin: 60px 0;
}

.signup-button {
    background-color: grey;
    color: white;
    border: none;
    padding: 14px 28px;
    font-size: 18px;
    border-radius: 8px;
    cursor: not-allowed;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.signup-note {
    margin-top: 10px;
    font-size: 14px;
    color: red;
}


footer {
    background-color: #531092;
    color: white;
    text-align: center;
    padding: 25px;
    margin-top: 60px;
    font-size: 16px;
    line-height: 1.6;
}

h3{
    color: white;
    font-size: 30px;
}


.call-button {
    background-color: grey;
    color: white;
    border: none;
    padding: 12px 24px;
    font-size: 20px;
    border-radius: 6px;
    cursor: not-allowed;
    margin-top: 10px;
}

.call-note {
    color: red;
    font-size: 14px;
    margin-top: 5px;
}


