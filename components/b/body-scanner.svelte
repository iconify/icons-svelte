<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rggpjjiew"/><rect class="tid5ihbau"/><path class="iiy2wsbze"/><circle class="uk55qvbnt"/><path class="kq_3o2btk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:body-scanner" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iiy2wsbze) {
  d: path("M5.75 3.5h12.5");
}

:global(.kq_3o2btk) {
  d: path("M8.75 21.25V17a3.25 3.25 0 0 1 6.5 0v4.25ZM11 18h2");
}

:global(.rggpjjiew) {
  width: 3px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

:global(.tid5ihbau) {
  width: 3px;
  height: 18.5px;
  x: 18.25px;
  y: 2.75px;
  rx: 1px;
}

:global(.uk55qvbnt) {
  cx: 12px;
  cy: 8.75px;
  r: 2px;
}

</style>
