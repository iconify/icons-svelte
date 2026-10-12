<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pujkrub0n"/><path class="nrm_r1bfd"/><path class="ywkpp0bhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bungalow-sharp" {...props}></Icon>
<style>
:global(.nrm_r1bfd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-4.5h3v4.5");
}

:global(.pujkrub0n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.56 10.16l7.63-5.57L12 4l.81.59l7.63 5.57l.81.59H2.75zm1.19 3.09h14.5v8H4.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ywkpp0bhy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16.5h.01m8.99 0h.01");
}

</style>
