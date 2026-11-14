<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azn4ak1ej"/><path class="z1h2opfkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mood-sunny" {...props}></Icon>
<style>
:global(.azn4ak1ej) {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm6-10v1.5m0 17V22M2 12h1.5m17 0H22M5 5l1 1m13-1l-1 1M5 19l1-1m13 1l-1-1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z1h2opfkt) {
  d: path("M9.25 13.5q2.75 2.5 5.5 0M10 10h.01M14 10h.01");
}

</style>
