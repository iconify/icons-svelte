<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jk-cxmm4a"/><path class="uherkgb3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:korfball" {...props}></Icon>
<style>
:global(.jk-cxmm4a) {
  d: path("M9.5 5a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0Z");
}

:global(.uherkgb3d) {
  d: path("M9.5 5v5a5 1.75 0 0 0 10 0V5M6 4v17.5M6 9h3.5M3 21.5h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
