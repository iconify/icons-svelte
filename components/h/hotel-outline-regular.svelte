<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="e_zu0lb2f"/><path class="uxsptjbvt"/><path class="e-07m9b9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hotel-outline-regular" {...props}></Icon>
<style>
:global(.d5czi6rdr) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.e_zu0lb2f) {
  d: path("M10 22v-5h4v5");
}

:global(.e-07m9b9c) {
  d: path("M6 11h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uxsptjbvt) {
  d: path("M6 7h12");
}

</style>
