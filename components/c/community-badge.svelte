<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8uwz1n7s"/><path class="zkk8x_zje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:community-badge" {...props}></Icon>
<style>
:global(.f8uwz1n7s) {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zkk8x_zje) {
  d: path("M9.25 9a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm-.75 5l-1.75 7L12 18.5l5.25 2.5l-1.75-7");
}

</style>
