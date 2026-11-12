<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v3bnzubkl"/><path class="s5xpay_7j"/><path class="tonplxqkt"/><path class="pre11cbbs"/><path class="qtz6yi5yq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-down-broken" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pre11cbbs) {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

:global(.qtz6yi5yq) {
  d: path("M20 10L9.5 10M5.25 10H3");
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
