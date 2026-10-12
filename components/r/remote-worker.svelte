<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hajmoyu0i"/><rect class="ry1ztcbjt"/><path class="sj0eok4lr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:remote-worker" {...props}></Icon>
<style>
:global(.hajmoyu0i) {
  cx: 12px;
  cy: 8.75px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ry1ztcbjt) {
  width: 11px;
  height: 5.25px;
  x: 6.5px;
  y: 13.5px;
  rx: 1px;
}

:global(.sj0eok4lr) {
  d: path("M3.75 21.25h16.5M2.75 10L12 2.75L21.25 10");
}

</style>
