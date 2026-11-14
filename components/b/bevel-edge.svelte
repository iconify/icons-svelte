<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qd76eacjc"/><path class="gy5m94b2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bevel-edge" {...props}></Icon>
<style>
:global(.gy5m94b2l) {
  d: path("M3 9h8l4 4v8M11 9l6-6m-2 10l6-6");
}

:global(.qd76eacjc) {
  d: path("M3 21V9l6-6h8l4 4v8l-6 6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
