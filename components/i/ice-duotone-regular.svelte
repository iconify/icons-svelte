<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c6v5n0q2l"/><path class="plts5tbsc"/><path class="e70mzkkad"/><path class="ricsl-blc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ice-duotone-regular" {...props}></Icon>
<style>
:global(.c6v5n0q2l) {
  fill: currentColor;
  d: path("M6 4h12v11l-6 6 -6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e70mzkkad) {
  d: path("m6 9 3 3h6l3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.plts5tbsc) {
  d: path("M6 4h12v11l-6 6 -6 -6Z");
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

</style>
