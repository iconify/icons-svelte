<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><circle class="o5grrub_r"/><path class="t0u1xzm4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:post-card" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o5grrub_r) {
  cx: 7px;
  cy: 7px;
  r: 1.5px;
}

:global(.t0u1xzm4y) {
  d: path("M10.5 7H17M6.5 12h11m-11 4h7");
}

</style>
