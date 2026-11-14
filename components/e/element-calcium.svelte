<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="w68wbccql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:element-calcium" {...props}></Icon>
<style>
:global(.j_psw1y4g) {
  d: path("M3 3h18v18H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w68wbccql) {
  d: path("M9.5 10.5h5A2 2 0 1 1 17 12a2 2 0 1 1-2.5 1.5h-5A2 2 0 1 1 7 12a2 2 0 1 1 2.5-1.5Z");
}

</style>
