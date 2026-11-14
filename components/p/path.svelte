<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kqa31eb8z"/><path class="uxs7z_bvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:path" {...props}></Icon>
<style>
:global(.kqa31eb8z) {
  d: path("M9.5 18.5H14a3 3 0 0 0 0-6h-4a3 3 0 0 1 0-6h4m2.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uxs7z_bvx) {
  fill: currentColor;
  d: path("M3.25 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
