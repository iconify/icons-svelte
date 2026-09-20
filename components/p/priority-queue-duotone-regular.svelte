<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wx106lesi"/><path class="ctew3dbzs"/><path class="w7io4q8th"/><path class="xwujyqqah"/><path class="ssv_ut7sw"/><path class="zuuudpbwi"/><path class="kh31pt5af"/><path class="t99bgtbzx"/><path class="ecismzb4h"/><path class="mo-r4ib5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:priority-queue-duotone-regular" {...props}></Icon>
<style>
:global(.ctew3dbzs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ecismzb4h) {
  d: path("M20 15V9");
}

:global(.kh31pt5af) {
  d: path("M3 13h14");
}

:global(.mo-r4ib5t) {
  d: path("m18 11 2 -2 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ssv_ut7sw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 11 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t99bgtbzx) {
  d: path("M3 18h14");
}

:global(.w7io4q8th) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wx106lesi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xwujyqqah) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 15V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
