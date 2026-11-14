<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qhuve9fxq"/><path class="jr__51hvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:classical-guitar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jr__51hvk) {
  d: path("M10.75 17.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

:global(.qhuve9fxq) {
  d: path("M10 14.5a2.5 2.5 0 1 1 4 0a3.75 3.75 0 1 1-4 0m2-4V6m0-3.5za1.25 1.25 0 0 1 1.25 1.25v1A1.25 1.25 0 0 1 12 6a1.25 1.25 0 0 1-1.25-1.25v-1A1.25 1.25 0 0 1 12 2.5");
}

</style>
