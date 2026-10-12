<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qvkly1bxc"/><rect class="du8-pxblr"/><path class="la-4dcbxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:port-usb-c" {...props}></Icon>
<style>
:global(.du8-pxblr) {
  width: 10px;
  height: 7.5px;
  x: 7px;
  y: 9.25px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.la-4dcbxe) {
  d: path("M12 16.75v4.5");
}

:global(.qvkly1bxc) {
  width: 8px;
  height: 4px;
  x: 8px;
  y: 2.75px;
  rx: 2px;
}

</style>
