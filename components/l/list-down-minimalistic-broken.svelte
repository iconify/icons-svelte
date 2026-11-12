<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pqx2-oyar"/><path class="tonplxqkt"/><path class="nmhvanepw"/><path class="pre11cbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-down-minimalistic-broken" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nmhvanepw) {
  d: path("M20 11L3 11");
}

:global(.pqx2-oyar) {
  d: path("M10 16H3");
}

:global(.pre11cbbs) {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

:global(.tonplxqkt) {
  stroke-linejoin: round;
  d: path("M14 15L17.5 18L21 15");
}

</style>
