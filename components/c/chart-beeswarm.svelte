<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sukohubkj"/><path class="h1333kbrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-beeswarm" {...props}></Icon>
<style>
:global(.h1333kbrj) {
  fill: currentColor;
  d: path("M2.25 11a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3-1.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3-5.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3-8.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3-8.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3-5.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm0 3.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm3-1.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.sukohubkj) {
  d: path("M2.5 20.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
