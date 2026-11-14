<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trjknbc8j"/><path class="lwfx2ju_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bean-bag-support" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwfx2ju_a) {
  d: path("M5.5 10c-2.5.5-3 4-3 7c0 2.75 1.5 4 4 4h11c2.5 0 4-1.25 4-4c0-3-.5-6.5-3-7M10 7.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.trjknbc8j) {
  d: path("M8.125 4h7.75A2.625 2.625 0 0 1 18.5 6.625v2.25a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 5.5 8.875v-2.25A2.625 2.625 0 0 1 8.125 4M10 4l1-1.5h2L14 4");
}

</style>
