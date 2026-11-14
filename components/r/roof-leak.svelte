<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="awjkif3ui"/><path class="h2qq0cbkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roof-leak" {...props}></Icon>
<style>
:global(.awjkif3ui) {
  d: path("M13.344 20.5H3.5v-10L12 3.25l6.108 5.21m.457.389L20.5 10.5v1.856");
}

:global(.h2qq0cbkg) {
  d: path("M7.5 20.5v-5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v5m6.75-6.5l-2.5 4.5a2.5 2.5 0 0 0 5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
