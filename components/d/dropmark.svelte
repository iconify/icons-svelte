<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":348};
const content = `<defs><path id="SVGTs95Vd5s" class="ef_hqztbd"/></defs><use href="#SVGTs95Vd5s" class="usvyhmbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:dropmark" {...props}></Icon>
<style>
:global(.ef_hqztbd) {
  d: path("M128 0S0 91.067 0 219.067c0 70.704 57.296 128 128 128s128-57.296 128-128C256 91.067 128 0 128 0m0 293.312l-68.68-79.051h30.61v-90.308h76.142v90.308h30.609z");
}

:global(.usvyhmbzy) {
  fill: var(--svg-color--38dedf, #38dedf);
}

</style>
