<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vyd1bmbqz"/><path class="qesyv5buv"/><path class="djbi_ub-i"/><path class="pre11cbbs"/><path class="qtz6yi5yq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-down-broken" {...props}></Icon>
<style>
:global(.djbi_ub-i) {
  d: path("M11 18H3");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pre11cbbs) {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

:global(.qesyv5buv) {
  d: path("M11 14L3 14");
}

:global(.qtz6yi5yq) {
  d: path("M20 10L9.5 10M5.25 10H3");
}

:global(.vyd1bmbqz) {
  stroke-linejoin: round;
  d: path("M20 17.5L17.5 20L15 17.5M17.5 20V14");
}

</style>
