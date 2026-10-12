<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j0vlx6bgz"/><path class="cvvmbgblk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pregnancy-test-sharp" {...props}></Icon>
<style>
:global(.cvvmbgblk) {
  d: path("M9.5 7.5h5V14h-5zM12 9.25v3M7 16.5h10");
}

:global(.j0vlx6bgz) {
  d: path("M7 2.75h10v18.5H7z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
