<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ndmyj0ctx"/><path class="l7xf9eb2w"/><rect class="qczhm1bne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alarm-sensor-door" {...props}></Icon>
<style>
:global(.l7xf9eb2w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 12h.01");
}

:global(.ndmyj0ctx) {
  width: 11px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.qczhm1bne) {
  width: 3.25px;
  height: 6px;
  x: 18px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
