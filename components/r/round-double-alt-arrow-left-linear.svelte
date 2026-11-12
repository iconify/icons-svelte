<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="b7cy1bbwm"/><path class="fa8kidbzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-left-linear" {...props}></Icon>
<style>
:global(.b7cy1bbwm) {
  stroke-linejoin: round;
  d: path("M15.5 9L12.5 12L15.5 15");
}

:global(.fa8kidbzr) {
  stroke-linejoin: round;
  d: path("M11.5 9L8.5 12L11.5 15");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

</style>
