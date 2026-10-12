<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yu377lxga"/><path class="ui9w7kory"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:harmonica" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ui9w7kory) {
  d: path("M2.75 10.25h18.5m-18.5 3.5h18.5M6 11.5v1m3.25-1v1m3.25-1v1m3.25-1v1m3.25-1v.01");
}

:global(.yu377lxga) {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2px;
}

</style>
