<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y97qv8bkx"/><path class="csq8_ef7k"/><path class="cxj77wb9c"/><path class="yvqy4kr7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:graduation-cap-toss-sharp" {...props}></Icon>
<style>
:global(.csq8_ef7k) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.72 10.52l.71 3.33c.26 1.22 2.42 1.78 4.87 1.26c2.44-.52 4.19-1.91 3.93-3.13l-.7-3.33m2.98-2.78v5");
}

:global(.cxj77wb9c) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.51 11.37h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.y97qv8bkx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.96 8.83l6.25-4.98l.59-.47l.73.19l7.74 2.01l.73.19l-.59.47l-6.25 4.98l-.59.47l-.73-.19L4.1 9.49l-.73-.19z");
}

:global(.yvqy4kr7w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 13.75l.375 2.625L6.5 17.5m-.75 2.75l2.2 1.1l2.55-.85");
}

</style>
