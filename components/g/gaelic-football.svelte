<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ek5k4ehan"/><path class="ka69rlo2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gaelic-football" {...props}></Icon>
<style>
:global(.ek5k4ehan) {
  d: path("M4 2.5v19M4 14h16m0-11.5v19M8.25 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ka69rlo2l) {
  d: path("M8.75 9.25q3.25-2.25 6.5 0");
}

</style>
