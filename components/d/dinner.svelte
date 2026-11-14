<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq5gnmblz"/><path class="hizmhcc1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dinner" {...props}></Icon>
<style>
:global(.eq5gnmblz) {
  d: path("M8.25 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M2.5 3v5a1.5 1.5 0 0 0 3 0V3M4 9.5V21m15.5 0V3c2 1.5 2 6 2 9.5h-2");
}

:global(.hizmhcc1l) {
  d: path("M11 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
