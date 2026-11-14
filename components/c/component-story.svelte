<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fti4mbcuq"/><path class="up54fvb6t"/><path class="n_npagbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:component-story" {...props}></Icon>
<style>
:global(.fti4mbcuq) {
  d: path("M5 19V5a2.5 2.5 0 0 1 2.5-2.5h12v19h-12A2.5 2.5 0 0 1 5 19Z");
}

:global(.n_npagbzt) {
  fill: currentColor;
  d: path("m12.25 5l1.5 1.5l-1.5 1.5l-1.5-1.5Zm0 6l1.5 1.5l-1.5 1.5l-1.5-1.5Zm-3-3l1.5 1.5l-1.5 1.5l-1.5-1.5Zm6 0l1.5 1.5l-1.5 1.5l-1.5-1.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.up54fvb6t) {
  d: path("M5 19a2.5 2.5 0 0 1 2.5-2.5h12");
}

</style>
