<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z5nb6qbkq"/><path class="y0a7sccky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:galley" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0a7sccky) {
  d: path("M14.5 15h5v3.5A2.5 2.5 0 0 1 17 21a2.5 2.5 0 0 1-2.5-2.5Zm5 1h.75a1.5 1.5 0 0 1 0 3h-.75");
}

:global(.z5nb6qbkq) {
  d: path("M11.9 20H2.5V3h15v9.2M10 3v17M7 9v3m6-3v3");
}

</style>
