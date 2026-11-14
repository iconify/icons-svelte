<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="le9oa03uf"/><path class="c3wstfbna"/><path class="l88d_k9mo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:course-complete" {...props}></Icon>
<style>
:global(.c3wstfbna) {
  d: path("M3 10v3a9 5.5 0 0 0 18 0v-3");
}

:global(.l88d_k9mo) {
  d: path("m8.5 10l2.5 2.25l4.5-4.5");
}

:global(.le9oa03uf) {
  d: path("M3 10a9 5.5 0 1 0 18 0a9 5.5 0 1 0-18 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
