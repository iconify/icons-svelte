<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oibtokbpn"/><path class="n74kd0bdc"/><path class="pih-07btv"/><path class="x9_hi749k"/><path class="q6kjd1w_g"/><path class="u70k4y_qc"/><path class="fevuzkbbx"/><path class="bfcwd7bcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:escalate-human-duotone-thin" {...props}></Icon>
<style>
:global(.bfcwd7bcm) {
  d: path("M13 13a4 4 0 0 1 8 0");
}

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

:global(.n74kd0bdc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 13.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oibtokbpn) {
  fill: currentColor;
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pih-07btv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q6kjd1w_g) {
  d: path("M7.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.u70k4y_qc) {
  d: path("m9 15 5 -5");
}

:global(.x9_hi749k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
