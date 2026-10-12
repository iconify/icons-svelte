<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="tq6mqfbto"/><path class="nsd-gy-mf"/><path class="tq_7myb4n"/><path class="w3ptzmp9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:network-switch" {...props}></Icon>
<style>
:global(.nsd-gy-mf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 17h2m2.5 0h2");
}

:global(.tq_7myb4n) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 17h.01");
}

:global(.tq6mqfbto) {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 12.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.w3ptzmp9a) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5h15m-1.75-1.75L19.5 4.5l-1.75 1.75m1.75 2.5h-15M6.25 7L4.5 8.75l1.75 1.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
