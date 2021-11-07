<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte'
    import Footer from '$lib/Footer.svelte'
    let myInfo = {
    title: "Info",
    item1: "Tiew Rui Zhe",
    item2: 13,
    item3: "SMJK (C) Chung Ling",
    }
    let myHobby = {
    title: "Hobby",
    item1: "Reading",
    item2: "Playing games",
    item3: "Coding",
    }
    let myPersonality = {
    title: "Personality",
    item1: "Quiet",
    item2: "Not handsome like Ernest",
    item3: "Humble",
    }
</script>
<Header title={"My Biography"}/>
<Section {...myInfo}/>
<Section {...myHobby}/>
<Section {...myPersonality}/>
<Footer github={"https://github.com/zhetiew/ruizhe-my-biography"}/>