<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pipuo_b0d"/><path class="r1_5jubgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:repeat-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pipuo_b0d) {
  stroke-opacity: 0.4;
  d: path("M3 13L3 6L21 6M17.7071 2.7071L21 6L17.7071 9.2929");
}

:global(.r1_5jubgn) {
  d: path("M21 11L21 18L3 18M6.2929 21.2929L3 18L6.2929 14.7071");
}

</style>
