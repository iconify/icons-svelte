<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sukohubkj"/><path class="uzu2glbys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-beeswarm" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sukohubkj) {
  d: path("M2.5 20.5h19");
}

:global(.uzu2glbys) {
  fill: currentColor;
  d: path("M2.25 11a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3-1.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3-5.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3-8.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3-8.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3-5.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3-1.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
