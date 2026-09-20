<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="g7cpaab_q"/><path class="rqhdq8b3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:listing-photo-outline-regular" {...props}></Icon>
<style>
:global(.d5czi6rdr) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.g7cpaab_q) {
  d: path("m6 9 3 -3 3 3 2 -2 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rqhdq8b3d) {
  d: path("M7 14.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2V17a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
