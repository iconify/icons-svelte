<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ajdaxebjd"/><rect class="wc8iu3btr"/><path class="vxegwhbjl"/><rect class="e2rclrsmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:convolution" {...props}></Icon>
<style>
:global(.ajdaxebjd) {
  width: 13px;
  height: 13px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

:global(.e2rclrsmn) {
  width: 4.5px;
  height: 4.5px;
  x: 16.75px;
  y: 2.75px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vxegwhbjl) {
  d: path("m10.5 11l6.25-4");
}

:global(.wc8iu3btr) {
  width: 5px;
  height: 5px;
  x: 5.5px;
  y: 11px;
  rx: 1px;
}

</style>
