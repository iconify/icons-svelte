<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jog0cvb4h"/><rect class="euzx67hrw"/><rect class="c_m5u3brr"/><path class="s1c60_bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:qr-code" {...props}></Icon>
<style>
:global(.c_m5u3brr) {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 13.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.euzx67hrw) {
  width: 7px;
  height: 7px;
  x: 13.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.jog0cvb4h) {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.s1c60_bus) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 6.75h.01m10.49 0h.01M6.75 17.25h.01m7.74-2.75h.01m5.49 0h.01m-2.76 2.75h.01M14.5 20h.01M20 20h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
