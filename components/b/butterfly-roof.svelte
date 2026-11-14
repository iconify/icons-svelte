<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dwgw5dbul"/><path class="fd489bixb"/><path class="utt68dznl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:butterfly-roof" {...props}></Icon>
<style>
:global(.dwgw5dbul) {
  d: path("M2.5 4.75L12 9.5l9.5-4.75");
}

:global(.fd489bixb) {
  d: path("M5 6v14.5h14V6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.utt68dznl) {
  d: path("M10 14.5h4v6h-4Z");
}

</style>
