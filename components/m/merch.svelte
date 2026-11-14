<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yixx-3b0m"/><path class="o7a78y-wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:merch" {...props}></Icon>
<style>
:global(.o7a78y-wx) {
  d: path("M9.25 15.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3-4.75L14 12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yixx-3b0m) {
  d: path("M8.5 3.5L3 6.5L4.75 11L7 10v10.5h10V10l2.25 1L21 6.5l-5.5-3C15 5.25 13.75 6.25 12 6.25s-3-1-3.5-2.75Zm3.75 7.5v4.75");
}

</style>
