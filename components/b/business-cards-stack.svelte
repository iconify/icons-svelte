<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2nq5gbuy"/><path class="dmx341b4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:business-cards-stack" {...props}></Icon>
<style>
:global(.dmx341b4m) {
  d: path("M6.5 9V7a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-2m-11-3h.01m2.99-1.5h5m-5 3H13");
}

:global(.f2nq5gbuy) {
  d: path("M6 9h8a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 14 19H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
