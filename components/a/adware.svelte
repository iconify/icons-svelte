<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jct3fj_gk"/><path class="j871lkdmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:adware" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j871lkdmh) {
  d: path("M13.875 11h5a2.625 2.625 0 0 1 2.625 2.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-5a2.625 2.625 0 0 1-2.625-2.625v-4.25A2.625 2.625 0 0 1 13.875 11M2.5 7h15M15 14.25l3 3m0-3l-3 3");
}

:global(.jct3fj_gk) {
  d: path("M8.5 16h-4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v3.25");
}

</style>
