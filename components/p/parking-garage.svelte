<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x2ihsrjln"/><path class="vojrdhb8t"/><rect class="xhcp3ibnu"/><path class="u24f3eowe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parking-garage" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u24f3eowe) {
  d: path("M16.25 9V5.5h1.5a1.25 1.25 0 0 1 0 2.5h-1.5");
}

:global(.vojrdhb8t) {
  d: path("M2.75 14.75h18.5m-18.5 3.5h18.5");
}

:global(.x2ihsrjln) {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 11.25px;
  rx: 0.75px;
}

:global(.xhcp3ibnu) {
  width: 7.5px;
  height: 8px;
  x: 13.75px;
  y: 3.25px;
  rx: 1px;
}

</style>
