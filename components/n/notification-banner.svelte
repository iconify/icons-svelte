<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em4j34a7u"/><path class="pe1auwbmd"/><path class="bd31zlbux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:notification-banner" {...props}></Icon>
<style>
:global(.bd31zlbux) {
  d: path("M12 10h6m-6 4h4");
}

:global(.em4j34a7u) {
  d: path("M2.5 6h19v12h-19Z");
}

:global(.pe1auwbmd) {
  fill: currentColor;
  d: path("M5.75 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
