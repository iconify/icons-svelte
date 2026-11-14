<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i-cs69-pp"/><path class="v-wr5abnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lie-detector" {...props}></Icon>
<style>
:global(.i-cs69-pp) {
  d: path("M3 14h18v6H3Zm3 0V4h12v10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-wr5abnc) {
  d: path("M6 9.5h2.5l1.5-2l2 3.5l1.5-3.5l1.5 2h3");
}

</style>
