<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="juo915b7k"/><path class="c65_rsb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-2-duocolor" {...props}></Icon>
<style>
:global(.c65_rsb5q) {
  d: path("M3 20h18m-9 0V6a2 2 0 0 0-2-2H7a2 2 0 0 0-2 2v14");
}

:global(.juo915b7k) {
  stroke-opacity: 0.4;
  d: path("m12 10.6l.75-.6a2 2 0 0 1 2.5 0l3 2.4a2 2 0 0 1 .75 1.56V20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
