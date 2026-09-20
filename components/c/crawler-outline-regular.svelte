<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lnkmmebvu"/><path class="qxnpdo0dk"/><path class="riylgsuoc"/><path class="kfdmhd64i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crawler-outline-regular" {...props}></Icon>
<style>
:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.lnkmmebvu) {
  d: path("M3 10a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qxnpdo0dk) {
  d: path("M3 10h14");
}

:global(.riylgsuoc) {
  d: path("M10 3a4.5 7 0 0 0 0 14 4.5 7 0 0 0 0 -14");
}

</style>
