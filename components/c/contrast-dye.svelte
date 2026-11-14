<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="stjez5bxy"/><path class="bi05fgdse"/><path class="e33mucbcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contrast-dye" {...props}></Icon>
<style>
:global(.bi05fgdse) {
  fill: currentColor;
  d: path("M2.5 8.5h8c1.5 1.5 1.5 5.5 0 7h-8Z");
}

:global(.e33mucbcs) {
  d: path("M14 12h5.5m-2-2l2 2l-2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.stjez5bxy) {
  d: path("M2.5 6h19m-19 12h19");
}

</style>
