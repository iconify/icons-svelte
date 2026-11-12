<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c6aatbbnu"/><path class="pqx2-oyar"/><path class="l4vllvb7o"/><path class="pre11cbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-check-minimalistic-broken" {...props}></Icon>
<style>
:global(.c6aatbbnu) {
  d: path("M10 11L3 11");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l4vllvb7o) {
  stroke-linejoin: round;
  d: path("M14 13.5L16.1 16L20 11");
}

:global(.pqx2-oyar) {
  d: path("M10 16H3");
}

:global(.pre11cbbs) {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

</style>
