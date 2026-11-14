<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tm48qdbnz"/><path class="w16r_mjxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carriage-loading" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tm48qdbnz) {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V7A3.5 3.5 0 0 1 6 3.5");
}

:global(.w16r_mjxo) {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M11.75 6.25h.5A1.75 1.75 0 0 1 14 8v4a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 12V8a1.75 1.75 0 0 1 1.75-1.75m-1.75 4h4");
}

</style>
