<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x4--r407h"/><path class="ab0kp1blk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ichthyosaur" {...props}></Icon>
<style>
:global(.ab0kp1blk) {
  d: path("M10.75 8.25c.75-2.25 1.75-3.5 3.5-4c-.75 1.5-.75 2.75-.25 3.5m-1 8q-.5 2.75-3.5 3.75q1-2.25.75-4.25m5-4h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x4--r407h) {
  d: path("m21.5 11.25l-4-1c-2-3.25-7-3.25-9.5 0L6 11.5L3.5 8h.75q1 4 0 8H3.5L6 12.5c2.5 3.5 8.5 4 11.5.75l4-1.25Z");
}

</style>
