<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jy1s42bgb"/><path class="tvgwi4boa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:envelope-parcel" {...props}></Icon>
<style>
:global(.jy1s42bgb) {
  d: path("M3.5 6h17v12h-17Z");
}

:global(.tvgwi4boa) {
  d: path("m3.5 8l8.5 6l8.5-6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
