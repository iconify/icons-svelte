<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gxy00ebpt"/><path class="i9cd8uk7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cross-greek" {...props}></Icon>
<style>
:global(.gxy00ebpt) {
  d: path("M9.5 2.5h5v19h-5Z");
}

:global(.i9cd8uk7c) {
  d: path("M2.5 9.5h19v5h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
