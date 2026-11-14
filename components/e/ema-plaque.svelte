<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tcys1hble"/><path class="dutezgbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ema-plaque" {...props}></Icon>
<style>
:global(.dutezgbht) {
  d: path("M8.5 7.25L12 2.5l3.5 4.75m-5 3.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-3 5h9");
}

:global(.tcys1hble) {
  d: path("m3 10l9-4.5l9 4.5v9.5H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
