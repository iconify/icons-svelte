<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wznzg3b9q"/><circle class="pbmr6pbso"/><path class="wa4d1qb6h"/><path class="hf69fobet"/><circle class="z1jlxibqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blood-pressure-cuff-sharp" {...props}></Icon>
<style>
:global(.hf69fobet) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 6.75h.01");
}

:global(.pbmr6pbso) {
  cx: 17.25px;
  cy: 6.75px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wa4d1qb6h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.25 6.75l2-2");
}

:global(.wznzg3b9q) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h8.5v12.5h-8.5zm2.75 3.5h3M5.5 12h3m2.75-3.5h2.5m-2.5 6.25h5.25V17");
}

:global(.z1jlxibqc) {
  cx: 16.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
