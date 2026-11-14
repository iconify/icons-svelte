<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q6epnvzpy"/><path class="oyyeq5b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-hose-reel" {...props}></Icon>
<style>
:global(.oyyeq5b6a) {
  d: path("M6.5 9.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 0v7m-1.5 0h3l-.75 4.5h-1.5Zm-5.5-7h.01");
}

:global(.q6epnvzpy) {
  d: path("M3.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
