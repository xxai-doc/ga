<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Moltar nódejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) a shuiteáil ar dtús, agus ansin `direnv allow` tar éis dul isteach san eolaire (déanfar [an .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) a fhorghníomhú go huathoibríoch tar éis dul isteach san eolaire).

Is é an bhrí: aistriúchán Sínis go Seapáinis, Cóiréis, Béarla, aistriúchán Béarla go dtí gach teanga eile. Mura dteastaíonn uait ach tacaíocht a thabhairt don tSínis agus don Bhéarla, ní féidir leat ach `zh: en` .

Is é an bhrí: aistriúchán Sínis go Seapáinis, Cóiréis, Béarla, aistriúchán Béarla go dtí gach teanga eile. Mura dteastaíonn uait ach tacaíocht a thabhairt don tSínis agus don Bhéarla, ní féidir leat ach `zh: en` .

* [cód tosaigh](https://github.com/xxai-art/web)
* [Pacaí teanga don suíomh ina iomláine](https://github.com/xxai-art/web/tree/main/i18n)
* [Pacáistí teanga do mhodúil logáil isteach](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Doiciméadúchán Ilteangach ar an Láithreán Gréasáin](https://github.com/xxai-doc)

Is í an teanga ríomhchlárúcháin tosaigh ag [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , a chuireann roinnt gnéithe bunaithe ar chomhréir coffeescript, féach [./coffee_plus.md](./coffee_plus.md) .

## Idirnáisiúnú láithreáin ghréasáin agus doiciméad

Tóg ar na 3 thionscadal seo a leanas

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Is é `.mdt` an iarmhír, is féidir leat an chomhréir cosúil le `<+ ./coffee_plus/import.js>` a úsáid chun tagairt a dhéanamh do chomhaid sheachtracha, agus marcáil síos a ghiniúint leis an iarmhír `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Ní aistreoidh aistriúchán Markdown cóid agus naisc, agus déanfaidh sé abairtí aistrithe a thaisceadh. Má athraítear an t-aistriúchán ach mura ndéantar an buntéacs a mhodhnú, ní fhorscríobhfar modhnú an aistriúcháin dá ndéanfaí é a fheidhmiú arís.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Comhaid teanga chun láithreáin ghréasáin ginte `yaml` a aistriú.

### Treoracha Uathoibriú Aistriú Doiciméad

Féach stór cóid [xxai-art/doc](https://github.com/xxai-art/doc)

Moltar nódejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) a shuiteáil ar dtús, agus ansin `direnv allow` tar éis dul isteach san eolaire (déanfar [an .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) a fhorghníomhú go huathoibríoch tar éis dul isteach san eolaire).

Chun an bonn cód mór aistrithe go na céadta teanga a sheachaint, chruthaigh mé bonn cód ar leith do gach teanga agus chruthaigh mé eagraíocht chun an bonn cód a stóráil

Má shocraítear an athróg timpeallachta `GITHUB_ACCESS_TOKEN` agus nuair a rithfear [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) cruthófar an stór cóid go huathoibríoch.

Ar ndóigh, is féidir leat é a chur i mbonn cód freisin.

Tagairt script aistriúcháin [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Léirmhínítear an cód scripte mar seo a leanas:

[Bunx](https://bun.sh/docs/cli/bunx) in ionad npx, atá níos tapúla. Ar ndóigh, mura bhfuil bun suiteáilte agat, is féidir leat `npx` a úsáid ina ionad sin.

Déanann `bunx mdt zh` `.mdt` sa chomhadlann zh mar `.md` , féach ar an 2 chomhad nasctha thíos

* [caife_móide.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [caife_móide.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` an croíchód le haghaidh aistriúcháin (mura bhfuil ach `nodejs` suiteáilte agat, ach nach bhfuil `bun` agus `direnv` suiteáilte, is féidir leat `npx i18n` a rith chun aistriúchán a dhéanamh).

Déanfaidh sé [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) a pharsáil , is é seo a leanas cumraíocht `i18n.yml` sa doiciméad seo:

```
en:
zh: ja ko en
```

Is é an bhrí: aistriúchán Sínis go Seapáinis, Cóiréis, Béarla, aistriúchán Béarla go dtí gach teanga eile. Mura dteastaíonn uait ach tacaíocht a thabhairt don tSínis agus don Bhéarla, ní féidir leat ach `zh: en` .

Is é an ceann deireanach ná [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , a bhaineann an t-ábhar idir an príomhtheideal agus an chéad fhotheideal de `README.md` gach teanga chun iontráil `README.md` . Tá an cód an-simplí, is féidir leat breathnú air tú féin.

Úsáidtear Google API le haghaidh aistriúcháin saor in aisce. Mura féidir leat rochtain a fháil ar Google, cumraigh agus socraigh seachfhreastalaí, mar:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Ginfidh an script aistriúcháin taisce aistrithe san eolaire `.i18n` , seiceáil le do thoil é le `git status` agus cuir leis an stór cód é chun athaistriúcháin a sheachaint.

Rith `bunx i18n` gach uair a athraíonn tú an t-aistriúchán chun an taisce a nuashonrú.

Má dhéantar an téacs bunaidh agus an t-aistriúchán a mhodhnú ag an am céanna, déanfar an taisce a mheascadh, mar sin más mian leat a mhodhnú, ní féidir leat ach ceann amháin a mhodhnú, agus ansin `bunx i18n` a reáchtáil chun an taisce a nuashonrú.
