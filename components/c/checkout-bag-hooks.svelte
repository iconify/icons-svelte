<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aa4mcj76t"/><path class="kftlajbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:checkout-bag-hooks" {...props}></Icon>
<style>
:global(.aa4mcj76t) {
  d: path("M2.5 4h19M4 4v4.5a1.75 1.75 0 0 0 3.5 0v-1M11 4v4.5a1.75 1.75 0 0 0 3.5 0v-1M18 4v4.5a1.75 1.75 0 0 0 3.5 0v-1");
}

:global(.kftlajbcn) {
  d: path("m5.75 10.25l-2 7.25a2 2 0 0 0 4 0Zm7 0l-2 7.25a2 2 0 0 0 4 0Zm7 0l-2 7.25a2 2 0 0 0 4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
