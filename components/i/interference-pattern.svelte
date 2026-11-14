<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ok0p5z5ai"/><path class="k9t7m5aoi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:interference-pattern" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k9t7m5aoi) {
  d: path("M2.5 12c1.5 6 3.25 6 4.75 0S10.5 6 12 12s3.25 6 4.75 0S20 6 21.5 12");
}

:global(.ok0p5z5ai) {
  d: path("M2.5 12C4 6 5.75 6 7.25 12s3.25 6 4.75 0s3.25-6 4.75 0s3.25 6 4.75 0");
}

</style>
