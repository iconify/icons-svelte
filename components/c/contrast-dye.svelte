<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="stjez5bxy"/><path class="bi05fgdse"/><path class="e33mucbcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contrast-dye" {...props}></Icon>
<style>
:global(.bi05fgdse) {
  fill: currentColor;
  d: path("M2.5 8.5h8c1.5 1.5 1.5 5.5 0 7h-8Z");
}

:global(.e33mucbcs) {
  d: path("M14 12h5.5m-2-2l2 2l-2 2");
}

:global(.stjez5bxy) {
  d: path("M2.5 6h19m-19 12h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
