<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ay5lgibsv"/><path class="bu0k5nbpn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-nightclub" {...props}></Icon>
<style>
:global(.ay5lgibsv) {
  d: path("M10 2.5V8m-6.5 6.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m0 0h13");
}

:global(.bu0k5nbpn) {
  d: path("M7 14.5a3 6.5 0 1 0 6 0a3 6.5 0 1 0-6 0m11-12Q18 5 20.5 5Q18 5 18 7.5Q18 5 15.5 5Q18 5 18 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
