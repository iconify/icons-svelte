<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8coymb2i"/><path class="p60c4uc3i"/><path class="vjo79vsth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:outlier" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8coymb2i) {
  fill: currentColor;
  d: path("M16.25 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.p60c4uc3i) {
  d: path("M14.25 6.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.vjo79vsth) {
  fill: currentColor;
  d: path("M3.25 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M7 13a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 7 13m-2 4.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m3.75-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-6 3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M7 20.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
