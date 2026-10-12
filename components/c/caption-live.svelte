<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mc5s_la1h"/><path class="drlhfzbvx"/><circle class="jo45v1frk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:caption-live" {...props}></Icon>
<style>
:global(.drlhfzbvx) {
  d: path("M6.25 10.25h8.5m-8.5 3.5h4m2 0h2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jo45v1frk) {
  cx: 19px;
  cy: 5px;
  r: 2.25px;
}

:global(.mc5s_la1h) {
  width: 15.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2.5px;
}

</style>
