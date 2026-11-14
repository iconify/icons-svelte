<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ax4-08ypa"/><path class="maqr-2b7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mango-tree" {...props}></Icon>
<style>
:global(.ax4-08ypa) {
  d: path("M3.5 8.5a8.5 6 0 1 0 17 0a8.5 6 0 1 0-17 0Zm8.5 6v7");
}

:global(.maqr-2b7s) {
  fill: currentColor;
  d: path("M5.75 15.25a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0Zm9.5 0a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
