<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kx8ydsb6b"/><path class="x-fa9emxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:achievement" {...props}></Icon>
<style>
:global(.kx8ydsb6b) {
  d: path("M7 3.5h10V9A5 5 0 0 1 7 9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-fa9emxj) {
  d: path("M7 5H4v2a3.5 3.5 0 0 0 3.25 3.5M17 5h3v2a3.5 3.5 0 0 1-3.25 3.5M12 14v4m-4.5 0h9v3h-9Z");
}

</style>
