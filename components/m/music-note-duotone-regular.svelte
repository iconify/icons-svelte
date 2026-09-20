<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="ezo88ccul"/><path class="w2qoutbxx"/><path class="mw0thacpt"/><path class="ew7y79byi"/><path class="huj3g_bus"/><path class="xob7qnbfo"/><path class="nycbsrkgh"/><path class="wwbyt5bkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-note-duotone-regular" {...props}></Icon>
<style>
:global(.ew7y79byi) {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ezo88ccul) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f6q7r5bds) {
  fill: currentColor;
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.huj3g_bus) {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.krwm4ebpd) {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mw0thacpt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nycbsrkgh) {
  d: path("M17 17V5");
}

:global(.w2qoutbxx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwbyt5bkd) {
  d: path("M9 5h8");
}

:global(.xob7qnbfo) {
  d: path("M9 17V5");
}

</style>
