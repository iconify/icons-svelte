<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nnt63_v-y"/><rect class="x5-wi1bdq"/><rect class="mpqnuacft"/><path class="hsr7r2yvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:call-stack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsr7r2yvh) {
  d: path("M4.5 20.75V4M2.75 5.75L4.5 4l1.75 1.75");
}

:global(.mpqnuacft) {
  width: 13px;
  height: 4.75px;
  x: 8.25px;
  y: 16.5px;
  rx: 1.5px;
}

:global(.nnt63_v-y) {
  width: 13px;
  height: 4.75px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.x5-wi1bdq) {
  width: 13px;
  height: 4.5px;
  x: 8.25px;
  y: 9.75px;
  rx: 1.5px;
}

</style>
