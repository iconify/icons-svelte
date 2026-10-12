<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="is-q8yaws"/><circle class="t66mq7qpn"/><path class="nntrnih8q"/><path class="fuldhtbew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:doorbell-cam" {...props}></Icon>
<style>
:global(.fuldhtbew) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 16a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0");
}

:global(.is-q8yaws) {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.nntrnih8q) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.5h.01");
}

:global(.t66mq7qpn) {
  cx: 12px;
  cy: 8.5px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
