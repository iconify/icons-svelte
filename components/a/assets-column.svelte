<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bos0j4biy"/><path class="v6h3a1xrk"/><path class="q9_6qwodb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:assets-column" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.q9_6qwodb) {
  d: path("M14 10h5v11h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6h3a1xrk) {
  fill: currentColor;
  d: path("M6 3h5v18H6Z");
}

</style>
