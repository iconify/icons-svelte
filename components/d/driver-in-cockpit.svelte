<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t66qvzb0k"/><path class="d9lf7tb7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:driver-in-cockpit" {...props}></Icon>
<style>
:global(.d9lf7tb7t) {
  d: path("M8.25 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-3.25-9.5h2.5");
}

:global(.t66qvzb0k) {
  d: path("M2.5 13V9H6v1h8.5l7 1.5V13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
