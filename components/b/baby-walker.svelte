<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5jo3t19k"/><path class="gnflflb_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-walker" {...props}></Icon>
<style>
:global(.d5jo3t19k) {
  d: path("M5 5.5a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0m-2 9a9 2.5 0 1 0 18 0a9 2.5 0 1 0-18 0m2-9l-2 9m16-9l2 9");
}

:global(.gnflflb_q) {
  d: path("M4.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
