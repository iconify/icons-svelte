<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k97cm6pbo"/><path class="kxw59qbgq"/><path class="mpmc0j4to"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-augmentation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k97cm6pbo) {
  d: path("M6 10h5.75a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-4.5A3.5 3.5 0 0 1 6 10");
}

:global(.kxw59qbgq) {
  d: path("M5.5 18.5L8.75 15l3.5 3.5M5.5 7H16a2 2 0 0 1 2 2v9.5");
}

:global(.mpmc0j4to) {
  d: path("m10 2.5l11.5 1.75l-.5 8.25");
}

</style>
