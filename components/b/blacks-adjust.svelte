<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w19d4-cem"/><path class="oqzgy6bji"/><path class="uo_t3hg_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blacks-adjust" {...props}></Icon>
<style>
:global(.oqzgy6bji) {
  fill: currentColor;
  d: path("M12.25 10.5h9.25v3h-9.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uo_t3hg_y) {
  d: path("M6 12h.01");
}

:global(.w19d4-cem) {
  d: path("M2.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
