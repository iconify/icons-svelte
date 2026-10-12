<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yd4kwwgnv"/><circle class="ejmel3lck"/><path class="qlp8a7bwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gauge" {...props}></Icon>
<style>
:global(.ejmel3lck) {
  cx: 12px;
  cy: 13.25px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qlp8a7bwg) {
  d: path("m13.28 11.71l2.47-2.96");
}

:global(.yd4kwwgnv) {
  d: path("M5.46 19.79a9.25 9.25 0 1 1 13.08 0");
}

</style>
