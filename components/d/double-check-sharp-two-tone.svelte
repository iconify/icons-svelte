<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="joslu-vdk"/><path class="cvcsfybdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:double-check-sharp-two-tone" {...props}></Icon>
<style>
:global(.cvcsfybdq) {
  d: path("M21.7407 10.7191L15.5 18L13.2071 15.7071");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.joslu-vdk) {
  stroke-opacity: 0.4;
  d: path("M2.2311 10.7118L7.1667 16L16.7964 5.6823");
}

</style>
