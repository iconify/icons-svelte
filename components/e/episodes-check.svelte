<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ky1exgdcg"/><path class="segm6mgwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:episodes-check" {...props}></Icon>
<style>
:global(.ky1exgdcg) {
  d: path("M3 8.5h18v11H3Zm2.5-3h13M8 2.5h8");
}

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

</style>
