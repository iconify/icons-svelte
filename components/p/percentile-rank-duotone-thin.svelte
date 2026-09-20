<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oibtokbpn"/><path class="yd1dd2b-v"/><path class="ueja73wqf"/><path class="wkf_8pb7a"/><path class="qrley9bmj"/><path class="ys-dg812g"/><path class="mjlof01ij"/><path class="ot1t9gb0r"/><path class="fevuzkbbx"/><path class="pubh6ib-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:percentile-rank-duotone-thin" {...props}></Icon>
<style>
:global(.fevuzkbbx) {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mjlof01ij) {
  d: path("M6 14.5v3");
}

:global(.oibtokbpn) {
  fill: currentColor;
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ot1t9gb0r) {
  d: path("M11 14.5v3");
}

:global(.pubh6ib-w) {
  d: path("M17 7v9");
}

:global(.qrley9bmj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ueja73wqf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wkf_8pb7a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 14.5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yd1dd2b-v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
