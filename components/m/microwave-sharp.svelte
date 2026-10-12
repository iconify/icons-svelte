<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ox05rfewb"/><path class="mv9nk1boe"/><path class="qjvyleyug"/><path class="knl2yx9sp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:microwave-sharp" {...props}></Icon>
<style>
:global(.knl2yx9sp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 15.75h1.5");
}

:global(.mv9nk1boe) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75h9v8.5h-9z");
}

:global(.ox05rfewb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

:global(.qjvyleyug) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 8.75h.01M18 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
