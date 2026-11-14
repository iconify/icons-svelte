<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qu4i8r00z"/><path class="j6i7cjuwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pet-dna-test" {...props}></Icon>
<style>
:global(.j6i7cjuwa) {
  d: path("M13.5 2.5c0 4.5-9 5-9 9c0 3.594 7.264 4.362 8.74 7.745M4.5 11.5h9m2.5 8a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0ZM15 16a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm2.75-1.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0ZM20.5 16a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.qu4i8r00z) {
  d: path("M4.5 2.5c0 4.5 9 5 9 9s-9 4.5-9 9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
