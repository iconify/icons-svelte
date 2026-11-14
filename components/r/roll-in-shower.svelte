<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g1g82abza"/><path class="q6e0agblr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roll-in-shower" {...props}></Icon>
<style>
:global(.g1g82abza) {
  d: path("M2.5 3.5H7a2 2 0 0 1 2 2V8");
}

:global(.q6e0agblr) {
  d: path("M5 12a4 4 0 0 1 8 0Zm1.5 2.5l-1 4m3.5-4v4m2.5-4L12 18m4.75-4.75h.01m-.26 2.5v2.75h3l1.5 3m-6.25-3a2.5 2.5 0 0 0 3.25 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
