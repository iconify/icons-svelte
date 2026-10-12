<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h0aclnbif"/><path class="bzlemrbpp"/><path class="zjt_73beb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:diving-flag-sharp" {...props}></Icon>
<style>
:global(.bzlemrbpp) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4.75 4l15 10.5");
}

:global(.h0aclnbif) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.5h16V15h-16Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zjt_73beb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 21.25V2.75");
}

</style>
