<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="glqecnbdi"/><path class="ga8jgcb7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:island-single-palm" {...props}></Icon>
<style>
:global(.ga8jgcb7e) {
  d: path("M12 16.5q-1-6 2-10.5m0 0q-4-2.5-8.5.5M14 6q4-2.5 7.5 1M14 6q-3 1-6 5m6-5q3.5 1.5 4.5 5");
}

:global(.glqecnbdi) {
  d: path("M2.5 19.5h19M5 19.5q7-6 14 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
