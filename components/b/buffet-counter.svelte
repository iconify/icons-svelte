<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5goyuy_i"/><path class="d07s-te_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:buffet-counter" {...props}></Icon>
<style>
:global(.d07s-te_v) {
  d: path("M7.5 11.25h3.25L10 14H8.25Zm5.75 0h3.25L15.75 14H14Z");
}

:global(.s5goyuy_i) {
  d: path("M2.5 14h19v5h-19Zm2 0a7.5 10.5 0 0 1 15 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
