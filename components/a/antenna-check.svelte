<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ed20gdc8m"/><path class="h_4q3k64b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:antenna-check" {...props}></Icon>
<style>
:global(.ed20gdc8m) {
  d: path("M8.5 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.h_4q3k64b) {
  d: path("M7.5 21.5L10 9l1.638 8.19m.412 2.059l.45 2.251m-7-18a6 6 0 0 0 0 8m9-8a6 6 0 0 1 0 8m.25 6.5l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
