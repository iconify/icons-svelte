<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iau37ab1m"/><path class="whwdtxbqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:computer-worm" {...props}></Icon>
<style>
:global(.iau37ab1m) {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.whwdtxbqg) {
  d: path("M6 11c1.5-3.5 4-3.5 5.5-1s4 2.5 5.5-1");
}

</style>
