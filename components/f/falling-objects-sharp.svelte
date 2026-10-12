<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qg1rkpyth"/><path class="b0jqmzm3a"/><path class="m7m59qc-v"/><path class="d2_dpab6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:falling-objects-sharp" {...props}></Icon>
<style>
:global(.b0jqmzm3a) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 9h2v2h-2Z");
}

:global(.d2_dpab6k) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 18a2.5 2.5 0 0 1 5 0");
}

:global(.m7m59qc-v) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.75h.01");
}

:global(.qg1rkpyth) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.98 4.99l7.29 13.02l.98 1.74H2.75l.98-1.74l7.29-13.02l.98-1.74z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
