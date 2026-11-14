<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f5bc8wb1q"/><path class="i4xbiwb9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:food-parcel" {...props}></Icon>
<style>
:global(.f5bc8wb1q) {
  d: path("M3 5h18v14H3Zm0 4.5h18");
}

:global(.i4xbiwb9i) {
  d: path("M10.5 5v7.5h3V5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
