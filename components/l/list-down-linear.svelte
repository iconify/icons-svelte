<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jv514ss1m"/><path class="rbjrgob2r"/><path class="v3bnzubkl"/><path class="s5xpay_7j"/><path class="tonplxqkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-down-linear" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jv514ss1m) {
  d: path("M21 6L3 6");
}

:global(.rbjrgob2r) {
  d: path("M21 10L3 10");
}

:global(.s5xpay_7j) {
  d: path("M10 18H3");
}

:global(.tonplxqkt) {
  stroke-linejoin: round;
  d: path("M14 15L17.5 18L21 15");
}

:global(.v3bnzubkl) {
  d: path("M10 14H3");
}

</style>
