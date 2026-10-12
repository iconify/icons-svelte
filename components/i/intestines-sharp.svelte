<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bd3lbb69b"/><path class="iwb6gehos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:intestines-sharp" {...props}></Icon>
<style>
:global(.bd3lbb69b) {
  d: path("M3.25 19.5V3.75h17.5v17h-3v-14H6.25V21h-3z");
}

:global(.iwb6gehos) {
  d: path("M10 9.25h5.25v2.5h-6.5v2.5h6.5v2.5h-6.5v2.5H12");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
