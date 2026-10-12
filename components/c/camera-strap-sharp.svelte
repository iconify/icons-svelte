<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="syiw7rbkg"/><path class="z81zjju8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:camera-strap-sharp" {...props}></Icon>
<style>
:global(.syiw7rbkg) {
  d: path("M4 9h16v11H4z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z81zjju8n) {
  d: path("M15 14.5a3 3 0 1 1-6 0a3 3 0 1 1 6 0M6.5 9L9 3.75h6L17.5 9");
}

</style>
