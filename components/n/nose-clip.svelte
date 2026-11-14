<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pdk93gbge"/><path class="bufljut-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nose-clip" {...props}></Icon>
<style>
:global(.bufljut-t) {
  d: path("M7 18a1.75 2.75 0 1 0 3.5 0A1.75 2.75 0 1 0 7 18m6.5 0a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pdk93gbge) {
  d: path("M8.75 15.25C6 12 5.5 4.5 12 4.5s6 7.5 3.25 10.75");
}

</style>
