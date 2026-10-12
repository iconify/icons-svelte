<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gx1xg5ykg"/><rect class="vaemujb5z"/><rect class="tf7-o_9ab"/><rect class="z4_h8kadi"/><rect class="kuil1ibpa"/><path class="ryr5h4n-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:risk-matrix" {...props}></Icon>
<style>
:global(.gx1xg5ykg) {
  d: path("M2.75 2.75v18.5h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kuil1ibpa) {
  width: 6px;
  height: 6px;
  x: 15.25px;
  y: 12.25px;
  rx: 1.5px;
}

:global(.ryr5h4n-k) {
  d: path("M18.25 4.5V6m0 1.25v.01");
}

:global(.tf7-o_9ab) {
  width: 6px;
  height: 6px;
  x: 15.25px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.vaemujb5z) {
  width: 6px;
  height: 6px;
  x: 5.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.z4_h8kadi) {
  width: 6px;
  height: 6px;
  x: 5.75px;
  y: 12.25px;
  rx: 1.5px;
}

</style>
