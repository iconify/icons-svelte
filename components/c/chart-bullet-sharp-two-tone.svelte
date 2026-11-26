<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hljch-bye"/><path class="p53xcyb3q"/><path class="cpby9zlid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-bullet-sharp-two-tone" {...props}></Icon>
<style>
:global(.cpby9zlid) {
  d: path("M7 10L21 10L21 14L7 14ZM16 6L16 18");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hljch-bye) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 9L21 9C21.5523 9 22 9.4477 22 10L22 14C22 14.5523 21.5523 15 21 15L7 15C6.4477 15 6 14.5523 6 14L6 10C6 9.4477 6.4477 9 7 9Z");
  stroke: none;
}

:global(.p53xcyb3q) {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

</style>
