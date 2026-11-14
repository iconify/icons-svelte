<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pnvn4uvom"/><path class="emzd9efec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-card" {...props}></Icon>
<style>
:global(.emzd9efec) {
  d: path("M7 11h10v6.5H7Zm5 0v6.5m-5-3.25h10");
}

:global(.pnvn4uvom) {
  d: path("M2.5 3.5h19v17h-19Zm4 4h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
