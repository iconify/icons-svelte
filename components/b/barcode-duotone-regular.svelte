<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ap9tz-pvm"/><path class="ay0-xnb_u"/><path class="l267babnk"/><path class="ro7j5915f"/><path class="yd5tqobrd"/><path class="nkim8cbjd"/><path class="azgrucbqu"/><path class="j5yfc7b4j"/><path class="btdmtu_xg"/><path class="vckqcjbbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barcode-duotone-regular" {...props}></Icon>
<style>
:global(.ap9tz-pvm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ay0-xnb_u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.azgrucbqu) {
  d: path("M7 5v14");
}

:global(.btdmtu_xg) {
  d: path("M14 5v14");
}

:global(.j5yfc7b4j) {
  d: path("M11 5v14");
}

:global(.l267babnk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nkim8cbjd) {
  d: path("M4 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ro7j5915f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vckqcjbbb) {
  d: path("M18 5v14");
}

:global(.yd5tqobrd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
