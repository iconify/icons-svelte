<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yr5xdz43b"/><path class="kzqrbvbtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bean-bag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kzqrbvbtp) {
  d: path("M12 6.5c2.5 4 3.5 8.75 2 14");
}

:global(.yr5xdz43b) {
  d: path("M5.5 20.75c-2.75 0-3.5-3.5-2-6.25C5 11 7 6 10 5.5q2 1.75 4 0c3 .5 5 5.5 6.5 9c1.5 2.75.75 6.25-2 6.25q-6.5 1-13 0");
}

</style>
