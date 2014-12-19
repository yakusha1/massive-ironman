 
Robotti joka seuraa linjaa ja jos robotin eteen tulee esteitä se ajaa esteen ympäri ja palaa
takas linjalle jatkamaan matkaa. Linjan tunnistus tapahtuu valosensorin avulla joka tapahtuu luokan LightSensor avulla ja esteiden tunnistaminen ja ohittaminen tapahtuu etäisyysmittarilla kutsujen int getDistance()  int readDistances(int [] distances), int continuous() avulla. Robotilla on kans käytös pari moottoria jotka ohjaavat laitteen eteenpäin. Ongelmana voi tulla isot esteet ja esteet mitkä on mahdotonta ohittaa.
Eli projektini on jaettu kahteen osaan. Ensimmäisessä osassa pitää tehdä robotti joka ajaa linjan pitkiin ja toisessa vaiheessa aloitan käyttää etäisyys sensoria jotka auttavat ohittaa esteen ja palata takaisin linjalle jatkamaan matka
