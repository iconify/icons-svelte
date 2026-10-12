<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gq28ubc8p"/><path class="kwoprz3hu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:headset-dj-sharp" {...props}></Icon>
<style>
:global(.gq28ubc8p) {
  d: path("M4.5 13.25V12a7.5 7.5 0 0 1 15 0v1.25");
}

:global(.kwoprz3hu) {
  d: path("M2.75 12.75h4.5v8h-4.5zm11.75.5h6.75v4.5H14.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
