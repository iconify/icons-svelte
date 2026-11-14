<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5sypd3oh"/><path class="dgsj05baa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:join-cross" {...props}></Icon>
<style>
:global(.dgsj05baa) {
  fill: currentColor;
  d: path("M2 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m16.5-15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x5sypd3oh) {
  d: path("M5.75 4.5h12.5m-12.5 15h12.5m-12.5-14l12.5 13m-12.5 0l12.5-13");
}

</style>
