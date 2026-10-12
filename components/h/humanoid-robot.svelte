<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="pfc5ew1xi"/><path class="mwns-9bhm"/><path class="kqef4tbqv"/><path class="tcl_u7zhf"/><path class="ttxdcjbnj"/><path class="xnnknu4ij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:humanoid-robot" {...props}></Icon>
<style>
:global(.kqef4tbqv) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.25h.01");
}

:global(.mwns-9bhm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.75V4");
}

:global(.pfc5ew1xi) {
  width: 13.5px;
  height: 12.5px;
  x: 5.25px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.tcl_u7zhf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5V16m18.5-3.5V16");
}

:global(.ttxdcjbnj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12.75h.01m5.49 0h.01");
}

:global(.xnnknu4ij) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 16.5h4.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
