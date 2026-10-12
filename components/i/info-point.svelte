<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="zen4tebxt"/><path class="tsdqsjo2p"/><path class="l3j0385pd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:info-point" {...props}></Icon>
<style>
:global(.l3j0385pd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5v2.75m0 2.5v7.5m-3.5 0h7");
}

:global(.tsdqsjo2p) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.75h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zen4tebxt) {
  width: 15.5px;
  height: 11px;
  x: 4.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

</style>
