<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="yvpdeub0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-blanket-sign" {...props}></Icon>
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

:global(.yvpdeub0q) {
  d: path("M6.5 5.5h11v1.75L15 9.75H6.5ZM15 9.75v-2.5h2.5m-5.5 11c-2.25 0-3.25-1.5-3.25-2.75s1.25-2 2-3c1 .75 1.25 1.5 1 2.25q1.5-.75 1.5-2.25c1.25 1 2 2 2 3.25c0 1.5-1 2.5-3.25 2.5Z");
}

</style>
