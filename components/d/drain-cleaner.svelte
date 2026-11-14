<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z32-znt-c"/><path class="l9hu2h1fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:drain-cleaner" {...props}></Icon>
<style>
:global(.l9hu2h1fj) {
  d: path("M9 12h6v5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z32-znt-c) {
  d: path("M9.5 2.5h5V6L18 9v10.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V9l3.5-3Z");
}

</style>
