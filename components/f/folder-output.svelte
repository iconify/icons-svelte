<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufvyl3eqx"/><path class="jsxndkb6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:folder-output" {...props}></Icon>
<style>
:global(.jsxndkb6g) {
  d: path("m20 12l1.5 1.5L20 15");
}

:global(.ufvyl3eqx) {
  d: path("M21 10V9a2 2 0 0 0-2-2h-7.5l-2-2H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2m-9-3.5h9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
