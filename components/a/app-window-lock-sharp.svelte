<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n_tbt4bnp"/><path class="h0757nbba"/><path class="vge_ec3ru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:app-window-lock-sharp" {...props}></Icon>
<style>
:global(.h0757nbba) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 6.5h.01m3.49 0h.01m3.49 0h.01");
}

:global(.n_tbt4bnp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5v17.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vge_ec3ru) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.75h17");
}

</style>
