import loadHome from './pages/home';
import loadMenu from './pages/menu';
import loadContact from './pages/contact';
import './style/style.css';


init();

function setBtnEvent(){
    const HomeBtn = document.getElementById("homeBtn")
    const menuBtn = document.getElementById("menuBtn")
    const contactBtn = document.getElementById("contactBtn")

    HomeBtn.addEventListener('click', loadHome);
    menuBtn.addEventListener('click', loadMenu);
    contactBtn.addEventListener('click', loadContact);
}
function a(){
    return 0;
}


function init(){
    loadHome();
    setBtnEvent();
}
