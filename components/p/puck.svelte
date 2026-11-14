<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzrszgbrj"/><path class="iijdzgbrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:puck" {...props}></Icon>
<style>
:global(.gzrszgbrj) {
  d: path("M3 9a9 4 0 1 0 18 0A9 4 0 1 0 3 9Z");
}

:global(.iijdzgbrx) {
  d: path("M3 9v5.5a9 4 0 0 0 18 0V9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
