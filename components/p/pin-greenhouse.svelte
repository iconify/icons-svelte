<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hf18p1lnb"/><path class="ybazt3bfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-greenhouse" {...props}></Icon>
<style>
:global(.hf18p1lnb) {
  d: path("M3 20.5v-8a9 9 0 0 1 18 0v8Zm.25-10h17.5M12 3.5v7m0 10V15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybazt3bfp) {
  d: path("M12 17.5c0-2-1.75-3.25-4-3.25c0 2 1.75 3.25 4 3.25m0-1c0-2 1.75-3.25 4-3.25c0 2-1.75 3.25-4 3.25");
}

</style>
