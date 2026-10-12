<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kkhx57bjk"/><path class="yfigmvbek"/><rect class="c3znz8-kd"/><path class="aqeaxjbwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:green-building" {...props}></Icon>
<style>
:global(.aqeaxjbwd) {
  d: path("M16.25 10.25c0-3.25 1.5-5.9 4.5-6.75c.25 3.25-1.5 6.1-4.5 6.75");
}

:global(.c3znz8-kd) {
  width: 5.5px;
  height: 8.25px;
  x: 15.75px;
  y: 13px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kkhx57bjk) {
  width: 10.5px;
  height: 14.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2px;
}

:global(.yfigmvbek) {
  d: path("M6 10.5h4M6 14h4m-4 3.5h4");
}

</style>
