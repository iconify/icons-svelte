<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nfu3paclw"/><rect class="xtm28ccvs"/><path class="nm0yidbtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:door-handle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nfu3paclw) {
  width: 7px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 3.5px;
}

:global(.nm0yidbtw) {
  d: path("M7.25 14.5v3");
}

:global(.xtm28ccvs) {
  width: 10.5px;
  height: 4px;
  x: 10.75px;
  y: 6.5px;
  rx: 2px;
}

</style>
