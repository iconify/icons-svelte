<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxgie-r8m"/><path class="ezv3tmubj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hd-badge" {...props}></Icon>
<style>
:global(.ezv3tmubj) {
  d: path("M13.5 8.5H15a3.5 3.5 0 0 1 0 7h-1.5Z");
}

:global(.kxgie-r8m) {
  d: path("M2.5 5h19v14h-19Zm4 3.5v7m4-7v7m-4-3.5h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
