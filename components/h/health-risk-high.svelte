<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l_183db8r"/><path class="uvn0-qu9c"/><path class="g-g2v9b3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:health-risk-high" {...props}></Icon>
<style>
:global(.g-g2v9b3k) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 5.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.l_183db8r) {
  d: path("M8 2.5h8a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uvn0-qu9c) {
  fill: currentColor;
  d: path("M10 6.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
