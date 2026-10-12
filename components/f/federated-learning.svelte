<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="s1sbiaces"/><rect class="lrb3wnbfw"/><rect class="aydh7op0y"/><path class="uaz3xbczv"/><circle class="z6httfbqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:federated-learning" {...props}></Icon>
<style>
:global(.aydh7op0y) {
  width: 5px;
  height: 5px;
  x: 9.5px;
  y: 16.25px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lrb3wnbfw) {
  width: 5px;
  height: 5px;
  x: 16.25px;
  y: 2.75px;
  rx: 1.25px;
}

:global(.s1sbiaces) {
  width: 5px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.25px;
}

:global(.uaz3xbczv) {
  d: path("m7.75 7.75l1.8 1.27m6.7-1.27l-1.8 1.27M12 13.75v2.5");
}

:global(.z6httfbqu) {
  cx: 12px;
  cy: 10.75px;
  r: 3px;
}

</style>
