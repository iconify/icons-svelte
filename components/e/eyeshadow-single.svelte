<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uyhcd2l4f"/><path class="ux86bltyl"/><path class="gr4-jpcwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eyeshadow-single" {...props}></Icon>
<style>
:global(.gr4-jpcwy) {
  d: path("M7 16.5a5 2 0 1 0 10 0a5 2 0 1 0-10 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux86bltyl) {
  d: path("M2.5 16.5a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0Z");
}

:global(.uyhcd2l4f) {
  d: path("M4 7a8 4.5 0 1 0 16 0A8 4.5 0 1 0 4 7Z");
}

</style>
