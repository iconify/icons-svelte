<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a95ub6bhf"/><path class="cksmbgo1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cassette-deck" {...props}></Icon>
<style>
:global(.a95ub6bhf) {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V8A3.5 3.5 0 0 1 6 4.5");
}

:global(.cksmbgo1c) {
  d: path("M8.5 7.5h7a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3a3 3 0 0 1 3-3m.5 3h.01m5.99 0h.01M7 16.5h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
