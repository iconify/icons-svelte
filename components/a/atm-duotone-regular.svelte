<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qdrw7hb2a"/><path class="n-868jblo"/><path class="fm1j79plm"/><path class="og4-69b6c"/><path class="rv8gzbbzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:atm-duotone-regular" {...props}></Icon>
<style>
:global(.fm1j79plm) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.n-868jblo) {
  fill: currentColor;
  d: path("M7 5h10v5H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.og4-69b6c) {
  d: path("M7 5h10v5H7Z");
}

:global(.qdrw7hb2a) {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rv8gzbbzr) {
  d: path("M9 18v4h6v-4");
}

</style>
