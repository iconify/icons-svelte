<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ioi34ebjc"/><path class="ljdr8cciu"/><path class="m5r2z8-tr"/><path class="zfy6zkybo"/><path class="t0ucggbme"/><path class="n3ji5yb6f"/><path class="rzt8fd71i"/><path class="vezq7pbcc"/><path class="ymhuvfz3p"/><path class="hxtix3e9b"/><path class="y0y0ccsoe"/><path class="cxgftibra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chemical-reaction-duotone-bold" {...props}></Icon>
<style>
:global(.cxgftibra) {
  d: path("m12 10 2 2 -2 2");
}

:global(.hxtix3e9b) {
  d: path("M15 6v11h6V6");
}

:global(.ioi34ebjc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ljdr8cciu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6v11h6V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m5r2z8-tr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n3ji5yb6f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzt8fd71i) {
  d: path("M2 6h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t0ucggbme) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vezq7pbcc) {
  d: path("M3 6v11h6V6");
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.ymhuvfz3p) {
  d: path("M14 6h8");
}

:global(.zfy6zkybo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 6v11h6V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
