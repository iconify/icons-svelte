<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7d56fjnv"/><path class="o4zw09imi"/><path class="vyks9vbfn"/><path class="rw6ho_bav"/><path class="vm55gtbfg"/><path class="lu8oixugf"/><path class="rta1163tv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:report-card-duotone-regular" {...props}></Icon>
<style>
:global(.g7d56fjnv) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lu8oixugf) {
  d: path("M13 13h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o4zw09imi) {
  fill: currentColor;
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rta1163tv) {
  d: path("M13 17h6");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.vm55gtbfg) {
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
