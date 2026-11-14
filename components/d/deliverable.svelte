<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zc9b-gbbi"/><path class="segm6mgwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deliverable" {...props}></Icon>
<style>
:global(.segm6mgwt) {
  d: path("m8.5 14l2.5 2.5l4.5-4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zc9b-gbbi) {
  d: path("M3 3.5h18v5H3Zm1.5 5v10a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-10");
}

</style>
