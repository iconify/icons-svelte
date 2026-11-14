<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utrhhsbxt"/><path class="i_7dmc9lu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-hot-dog" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_7dmc9lu) {
  d: path("M7.5 12q1.25-1 2.5 0t2.5 0t2.5 0t2.5 0");
}

:global(.utrhhsbxt) {
  d: path("M5.5 9h13a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3a3 3 0 0 1 3-3M6 9c0-2 2-3.5 4.5-3.5h3C16 5.5 18 7 18 9M6 15c0 2 2 3.5 4.5 3.5h3C16 18.5 18 17 18 15");
}

</style>
