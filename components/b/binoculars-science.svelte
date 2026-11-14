<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uza2veb8u"/><path class="v5c68rj7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:binoculars-science" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uza2veb8u) {
  d: path("M2.5 15.5V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5m3 0V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5");
}

:global(.v5c68rj7q) {
  d: path("M2.5 15.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3-6.5h3");
}

</style>
