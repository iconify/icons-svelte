<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j7sj82kwz"/><path class="vgq1lnv0l"/><path class="lz5i7ta_k"/><path class="bp3yu1oem"/><path class="d0n0p9bwt"/><path class="mz0o03tol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-right-duotone-regular" {...props}></Icon>
<style>
:global(.bp3yu1oem) {
  d: path("M12 22v-9l7 -7");
}

:global(.d0n0p9bwt) {
  d: path("M19 10.5V6h-4.5");
}

:global(.j7sj82kwz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 22v-9l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lz5i7ta_k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11 5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mz0o03tol) {
  d: path("M10 11 5 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vgq1lnv0l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 10.5V6h-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
