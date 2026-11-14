<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uhf59lrjm"/><path class="hj_a7sb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:quadrant-lower-right" {...props}></Icon>
<style>
:global(.hj_a7sb7a) {
  fill: currentColor;
  d: path("M12 18.5A9.5 9.5 0 0 0 21.5 9H17a5 5 0 0 1-5 5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uhf59lrjm) {
  d: path("M2.5 5.5V9a9.5 9.5 0 0 0 19 0V5.5H17V9A5 5 0 0 1 7 9V5.5Z");
}

</style>
