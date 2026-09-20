<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pq9ly31-r"/><path class="iup9trbmr"/><path class="w92rm08yv"/><path class="t0-mwc0xy"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:n-plus-one-outline-regular" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.iup9trbmr) {
  d: path("M12 6v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pq9ly31-r) {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.w92rm08yv) {
  d: path("M4 16v-6h16v6");
}

</style>
