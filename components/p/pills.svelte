<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g0gbqmb1l"/><path class="whfby4ybr"/><rect class="uozso8b5o"/><path class="x9ffbhbfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pills" {...props}></Icon>
<style>
:global(.g0gbqmb1l) {
  cx: 8.5px;
  cy: 8.5px;
  r: 5.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uozso8b5o) {
  width: 9.5px;
  height: 6px;
  x: 11.75px;
  y: 15.25px;
  rx: 3px;
}

:global(.whfby4ybr) {
  d: path("m5.25 11.75l6.5-6.5");
}

:global(.x9ffbhbfz) {
  d: path("M16.5 15.25v6");
}

</style>
