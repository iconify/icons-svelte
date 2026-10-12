<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tiq214b2f"/><path class="qzli-fbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chalkboard" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qzli-fbyk) {
  d: path("M6.75 7.75h7.5m-7.5 4h4.5m-4 4.5l-1.5 5m11-5l1.5 5");
}

:global(.tiq214b2f) {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

</style>
