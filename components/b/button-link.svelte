<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rea3x2bzc"/><path class="ztgkbj65n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:button-link" {...props}></Icon>
<style>
:global(.rea3x2bzc) {
  d: path("M2.5 6.5h19v11h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ztgkbj65n) {
  d: path("M10 9.25H8.75a2.75 2.75 0 0 0 0 5.5H10m4-5.5h1.25a2.75 2.75 0 0 1 0 5.5H14M9.25 12h5.5");
}

</style>
