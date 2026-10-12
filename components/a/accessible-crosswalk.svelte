<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="t0v21rbsq"/><rect class="qa_ab_9cp"/><rect class="dqt5sjtdl"/><path class="pxmn6eb9l"/><path class="q9pnr2wro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:accessible-crosswalk" {...props}></Icon>
<style>
:global(.dqt5sjtdl) {
  width: 4px;
  height: 6.25px;
  x: 17.25px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.pxmn6eb9l) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3.5h.01");
}

:global(.q9pnr2wro) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6v3.25h3.25l1 2.5M9.15 7.6A2.75 2.75 0 1 0 13 11.75");
}

:global(.qa_ab_9cp) {
  width: 4px;
  height: 6.25px;
  x: 10px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.t0v21rbsq) {
  width: 4px;
  height: 6.25px;
  x: 2.75px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
