<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ds6j9e5nf"/><path class="jnqq21v7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-entrance" {...props}></Icon>
<style>
:global(.ds6j9e5nf) {
  d: path("M12.974 20.776L12 21.75L2.25 12L12 2.25L21.75 12l-1.917 1.917");
}

:global(.jnqq21v7p) {
  d: path("M9.75 16.5v-9H12a2.75 2.75 0 0 1 0 5.5H9.75M21 18h-6m2.5-2.5L15 18l2.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
