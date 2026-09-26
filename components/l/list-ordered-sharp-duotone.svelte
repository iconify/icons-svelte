<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i7-tzbbda"/><path class="t0z8_o3bg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-ordered-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.i7-tzbbda) {
  stroke-opacity: 0.4;
  d: path("M10 5L22 5M10 12L22 12M10 19L22 19");
}

:global(.t0z8_o3bg) {
  d: path("M3.5 4.5L5 3L5 8M2 8L8 8M3 16.3C3 15.5 3.84 15 4.89 15C6.05 15 7 15.7 7 16.7C7 18.6 3 19.9 3 21L8 21");
}

</style>
