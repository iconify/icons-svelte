<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ie-b5fmsf"/><path class="atv66_b1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:anemone" {...props}></Icon>
<style>
:global(.atv66_b1j) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ie-b5fmsf) {
  d: path("M14.5 8a3 3 0 1 1 2.25 4a3 3 0 1 1-2.25 4a3 3 0 1 1-5 0a3 3 0 1 1-2.25-4A3 3 0 1 1 9.5 8a3 3 0 1 1 5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
