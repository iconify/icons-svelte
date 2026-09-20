<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eff5yibna"/><path class="n74qqnw0j"/><path class="f1vz2n_od"/><path class="pen5ukb_h"/><path class="xdhl9rnnf"/><path class="pq9ly31-r"/><path class="iup9trbmr"/><path class="w92rm08yv"/><path class="t0-mwc0xy"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:n-plus-one-duotone-regular" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.eff5yibna) {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f1vz2n_od) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16v-6h16v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iup9trbmr) {
  d: path("M12 6v4");
}

:global(.n74qqnw0j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pen5ukb_h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.xdhl9rnnf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
