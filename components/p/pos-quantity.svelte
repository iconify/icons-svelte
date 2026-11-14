<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5yyb4bor"/><path class="dk_bygbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pos-quantity" {...props}></Icon>
<style>
:global(.dk_bygbon) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v2.4M7.5 4.75l9 4.5m0 5.25l-.5 7m4-7l-.5 7m-5-4.75h7m-7 2.5h7");
}

:global(.k5yyb4bor) {
  d: path("M11.664 21.332L3 17V7l9-4.5L21 7v4.738");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
