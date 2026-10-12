<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xn3k12x2g"/><rect class="ya_0mfz6j"/><path class="kzqphpboj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:business-card" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kzqphpboj) {
  d: path("M6.75 11.25h6m-6 3.75h10.5");
}

:global(.xn3k12x2g) {
  d: path("M5.25 3.75h13.5");
}

:global(.ya_0mfz6j) {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
