<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gr0fknb3w"/><path class="i_pgfyvot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flying-side-kick" {...props}></Icon>
<style>
:global(.gr0fknb3w) {
  d: path("M3 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8 9l3 4.5h10m-10 0l-4 3l3 3.5");
}

:global(.i_pgfyvot) {
  d: path("m3.5 12l5-2.5l5-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
