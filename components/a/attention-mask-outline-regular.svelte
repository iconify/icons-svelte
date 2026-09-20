<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzpsuduik"/><path class="edg0x3nuq"/><path class="xsyfe-byx"/><path class="qfgxpvbvs"/><path class="ehef6tbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:attention-mask-outline-regular" {...props}></Icon>
<style>
:global(.edg0x3nuq) {
  d: path("m5 5 14 14");
}

:global(.ehef6tbzw) {
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.qfgxpvbvs) {
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xsyfe-byx) {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
