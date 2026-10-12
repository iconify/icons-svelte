<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bki_fti6o"/><path class="kmps77u7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:redo-all-sharp" {...props}></Icon>
<style>
:global(.bki_fti6o) {
  d: path("M19.75 9.25h-10a5.5 5.5 0 0 0 0 11H14");
}

:global(.kmps77u7k) {
  d: path("m15.75 5.25l4 4l-4 4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
