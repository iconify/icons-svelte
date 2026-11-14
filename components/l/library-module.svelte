<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4tmumiqc"/><path class="fhvry66nd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:library-module" {...props}></Icon>
<style>
:global(.d4tmumiqc) {
  d: path("m11 2.5l8 4l-8 4l-8-4Z");
}

:global(.fhvry66nd) {
  d: path("M3 6.5v4l8 4l4.164-2.082m.358-.179L19 10.5v-4m-8 4v4m-8 0l8 4l1.213-.606M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
