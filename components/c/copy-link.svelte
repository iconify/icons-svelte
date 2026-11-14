<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ail0y-9zd"/><path class="i1ih5k38s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:copy-link" {...props}></Icon>
<style>
:global(.ail0y-9zd) {
  d: path("M8.5 8.5h12v12h-12Z");
}

:global(.i1ih5k38s) {
  d: path("M4 14.5V6a2.5 2.5 0 0 1 2.5-2.5h8M13 12h-.5a2.5 2.5 0 0 0 0 5h.5m3-5h.5a2.5 2.5 0 0 1 0 5H16m-3-2.5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
