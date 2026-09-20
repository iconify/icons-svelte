<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="ex75cacie"/><path class="k_7z1bcnp"/><path class="y0jwkuckv"/><path class="c39r_abdo"/><path class="s8lctcbrd"/><path class="xgrfb-bqu"/><path class="xyj-l9cjp"/><path class="f26bn-hui"/><path class="l8vl6rdup"/><path class="dti01qb8s"/><path class="l76jezbpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paraphrase-duotone-regular" {...props}></Icon>
<style>
:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c39r_abdo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dti01qb8s) {
  d: path("M16 9v6");
}

:global(.ex75cacie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f26bn-hui) {
  d: path("M8 9v6");
}

:global(.k_7z1bcnp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l76jezbpv) {
  d: path("M13.5 11.5 16 9l2.5 2.5");
}

:global(.l8vl6rdup) {
  d: path("M5.5 12.5 8 15l2.5 -2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s8lctcbrd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 11.5 16 9l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.y0jwkuckv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 12.5 8 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
