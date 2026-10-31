<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="sp-37xbcp"/><path class="sf_30mb7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:luggage-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sf_30mb7o) {
  d: path("M8 6L9 2L15 2L16 6M7 20L7 23M17 20L17 23");
}

:global(.sp-37xbcp) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5L19 5C19.5523 5 20 5.4477 20 6L20 20C20 20.5523 19.5523 21 19 21L5 21C4.4477 21 4 20.5523 4 20L4 6C4 5.4477 4.4477 5 5 5ZM6 10L6 12L18 12L18 10L6 10Z");
  stroke: none;
}

</style>
