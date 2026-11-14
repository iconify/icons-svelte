<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gb5i19bsq"/><path class="rt5mfx-gr"/><path class="dxrobyi0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-bay-sensor" {...props}></Icon>
<style>
:global(.dxrobyi0r) {
  d: path("M8.995 11.995a4.25 4.25 0 0 1 6.01 0M6.873 9.873a7.25 7.25 0 0 1 10.254 0");
}

:global(.gb5i19bsq) {
  d: path("M4 5v15h16V5");
}

:global(.rt5mfx-gr) {
  fill: currentColor;
  d: path("M10.5 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
