<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eriu-9buc"/><path class="wn3d4hbqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-venn" {...props}></Icon>
<style>
:global(.eriu-9buc) {
  d: path("M2.5 12A6.25 6.25 0 1 0 15 12a6.25 6.25 0 1 0-12.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wn3d4hbqw) {
  d: path("M9 12a6.25 6.25 0 1 0 12.5 0A6.25 6.25 0 1 0 9 12Z");
}

</style>
