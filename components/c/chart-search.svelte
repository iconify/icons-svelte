<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eanni_blz"/><path class="k9-cvgb2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-search" {...props}></Icon>
<style>
:global(.eanni_blz) {
  d: path("M3.5 3v17.5h9.6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k9-cvgb2t) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-4.25 12.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.5 2l2.25 2.25");
}

</style>
