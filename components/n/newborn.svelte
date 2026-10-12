<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jgv7wobfh"/><circle class="argn9bbqd"/><path class="ktnabfbml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:newborn" {...props}></Icon>
<style>
:global(.argn9bbqd) {
  cx: 12px;
  cy: 8.25px;
  r: 2.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgv7wobfh) {
  width: 10.5px;
  height: 18.25px;
  x: 6.75px;
  y: 3px;
  rx: 5.25px;
}

:global(.ktnabfbml) {
  d: path("m6.75 13.5l10.5 3.5");
}

</style>
