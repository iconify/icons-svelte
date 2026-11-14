<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ia96wwzqm"/><path class="gou7cxbcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:abandoned-cart-email" {...props}></Icon>
<style>
:global(.gou7cxbcf) {
  d: path("m3 6.5l9 6l9-6m-6 11h7l-1 4h-5Zm1.5 0a2 2 0 0 1 4 0");
}

:global(.ia96wwzqm) {
  d: path("M12.5 19h-10V4h19v9.8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
