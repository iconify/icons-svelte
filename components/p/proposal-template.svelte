<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jtn9exb6d"/><path class="rl4qg70gb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:proposal-template" {...props}></Icon>
<style>
:global(.jtn9exb6d) {
  d: path("M4 2.5h16v19H4Zm3 4h10");
}

:global(.rl4qg70gb) {
  d: path("M7 9.5h10V14H7Zm0 8.25h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
