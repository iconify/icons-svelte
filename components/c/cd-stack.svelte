<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v3ft4eaog"/><path class="grlkcu0bg"/><path class="lrgl4jfzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cd-stack" {...props}></Icon>
<style>
:global(.grlkcu0bg) {
  d: path("M17.471 14.464a6 6 0 1 1-7.935-7.935");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lrgl4jfzx) {
  d: path("M14.471 17.464a6 6 0 1 1-7.935-7.935M13.25 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.v3ft4eaog) {
  d: path("M9 9a6 6 0 1 0 12 0A6 6 0 1 0 9 9");
}

</style>
