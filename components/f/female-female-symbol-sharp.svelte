<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="euh_8jbah"/><path class="ubpr89usi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:female-female-symbol-sharp" {...props}></Icon>
<style>
:global(.euh_8jbah) {
  d: path("M9 3.75a4.75 4.75 0 1 1 0 9.5a4.75 4.75 0 1 1 0-9.5m0 9.5v8m-1.5-3.5h3");
}

:global(.ubpr89usi) {
  d: path("M15 3.75a4.75 4.75 0 1 1 0 9.5a4.75 4.75 0 1 1 0-9.5m0 9.5v8m-1.5-3.5h3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
