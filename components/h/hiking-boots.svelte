<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ygx6k37om"/><path class="t58okeb6m"/><path class="jhjn901nq"/><rect class="ndo0d389p"/><path class="mu5n28q-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hiking-boots" {...props}></Icon>
<style>
:global(.jhjn901nq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.25h.01m-.01 3.25h.01");
}

:global(.mu5n28q-s) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 21.25V19.5m4.5 1.75V19.5m4.5 1.75V19.5");
}

:global(.ndo0d389p) {
  width: 17.5px;
  height: 4px;
  x: 3.25px;
  y: 17.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.t58okeb6m) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.25h4.5q1.5 0 1.5 1.5v.75q0 1.5 1.42 1.97l3.16 1.06q1.42.47 2.56 1.45l1.22 1.04q1.14.98 1.14 2.48v.25q0 1.5-1.5 1.5h-14q-1.5 0-1.5-1.5v-9q0-1.5 1.5-1.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ygx6k37om) {
  width: 8.5px;
  height: 2.5px;
  x: 3.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

</style>
