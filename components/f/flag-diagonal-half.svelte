<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ffwl019_e"/><path class="gaaogwstd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flag-diagonal-half" {...props}></Icon>
<style>
:global(.ffwl019_e) {
  d: path("M5 2.5v19m0-18h14v10H5Z");
}

:global(.gaaogwstd) {
  fill: currentColor;
  d: path("M5 3.5h14l-14 10Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
