<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wrqvllj2c"/><path class="gcp84n0uq"/><circle class="sz7o-pbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:camera-bag" {...props}></Icon>
<style>
:global(.gcp84n0uq) {
  d: path("M8.75 8.25V6.5a1.75 1.75 0 0 1 1.75-1.75h3a1.75 1.75 0 0 1 1.75 1.75v1.75M2.75 12h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sz7o-pbpi) {
  cx: 12px;
  cy: 16.25px;
  r: 2px;
}

:global(.wrqvllj2c) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

</style>
