<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="swh3zzbaa"/><path class="dy4cmmk2o"/><path class="y5v_nkxrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:championship-belt" {...props}></Icon>
<style>
:global(.dy4cmmk2o) {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

:global(.swh3zzbaa) {
  d: path("M6.25 9H3.5q-1 0-1 1v4q0 1 1 1h2.75m11.5-6h2.75q1 0 1 1v4q0 1-1 1h-2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y5v_nkxrd) {
  d: path("m12 8.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L12 13.75l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
