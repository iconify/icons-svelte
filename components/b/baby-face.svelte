<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ha9xtnb5j"/><path class="pjbbv2bym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-face" {...props}></Icon>
<style>
:global(.ha9xtnb5j) {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pjbbv2bym) {
  d: path("M12 5c-1-2 1.75-3 2.25-1.25M9 12.5h.01m5.99 0h.01M10 17q2 1.75 4 0");
}

</style>
