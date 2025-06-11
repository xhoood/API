.



javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/hackermoon1/sala-do-futuro-script@main/script.js';document.head.appendChild(s);})();


javascript:(function(){
  fetch("https://corsproxy.io/?https://raw.githubusercontent.com/hackermoon1/sala-do-futuro-script/main/script.js")
    .then(r => r.text())
    .then(code => eval(code))
    .catch(e => console.error("Erro ao carregar o script:", e));
})();
