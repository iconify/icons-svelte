<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="fub8u0bsr"/><path class="mvkasiemb"/><path class="tonplxqkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-down-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.fub8u0bsr) {
  d: path("M20 11L3 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mvkasiemb) {
  d: path("M10 16H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.s19aowben) {
  d: path("M20 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.tonplxqkt) {
  stroke-linejoin: round;
  d: path("M14 15L17.5 18L21 15");
}

</style>
