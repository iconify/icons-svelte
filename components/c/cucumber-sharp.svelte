<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pcx8i6l6y"/><path class="o3bi57sdq"/><circle class="iwer1wtdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cucumber-sharp" {...props}></Icon>
<style>
:global(.iwer1wtdo) {
  cx: 18px;
  cy: 18px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3bi57sdq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M13 10h.01");
}

:global(.pcx8i6l6y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.13 14.63l10-10a3 3 0 0 1 4.24 4.24l-10 10a3 3 0 0 1-4.24-4.24Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
