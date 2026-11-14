<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vvgcjrlwh"/><path class="v-kpp0bng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:noise-cancelling" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-kpp0bng) {
  d: path("M5.25 13.5zA1.75 1.75 0 0 1 7 15.25v4A1.75 1.75 0 0 1 5.25 21a1.75 1.75 0 0 1-1.75-1.75v-4a1.75 1.75 0 0 1 1.75-1.75m13.5 0za1.75 1.75 0 0 1 1.75 1.75v4A1.75 1.75 0 0 1 18.75 21A1.75 1.75 0 0 1 17 19.25v-4a1.75 1.75 0 0 1 1.75-1.75m-8.75 5l4-7");
}

:global(.vvgcjrlwh) {
  d: path("M3.5 16v-4a8.5 8.5 0 0 1 17 0v4");
}

</style>
