<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdsh-kpie"/><path class="dfsacyb3u"/><path class="e6b9y8b8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cup-draw" {...props}></Icon>
<style>
:global(.dfsacyb3u) {
  d: path("M5.5 4.5H3V6a3.5 3.5 0 0 0 3.25 3.5m8.25-5H17V6a3.5 3.5 0 0 1-3.25 3.5m-3.75 2v6m-3.5 0h4.7m2.8-2h1.25l4.25 5h2m-1.25-1.25l1.25 1.25l-1.25 1.25");
}

:global(.e6b9y8b8v) {
  d: path("M14 20.5h1.25l4.25-5h2m-1.25-1.25l1.25 1.25l-1.25 1.25");
}

:global(.jdsh-kpie) {
  d: path("M5.5 2.5h9V7a4.5 4.5 0 0 1-9 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
