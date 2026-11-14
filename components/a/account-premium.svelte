<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ey9s5ab8y"/><path class="uwni876fg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-premium" {...props}></Icon>
<style>
:global(.ey9s5ab8y) {
  d: path("m3 9l4-5h10l4 5l-9 10.5Zm0 0h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uwni876fg) {
  d: path("M8.5 9L12 4l3.5 5m-7 0L12 19.5L15.5 9");
}

</style>
