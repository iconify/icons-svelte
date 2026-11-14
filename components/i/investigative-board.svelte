<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a95ub6bhf"/><path class="ttec-px7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:investigative-board" {...props}></Icon>
<style>
:global(.a95ub6bhf) {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ttec-px7q) {
  d: path("M6 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m9-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-6.25 5.25l6.5-4.5M7 7.25h1a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H7a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 7 7.25");
}

</style>
