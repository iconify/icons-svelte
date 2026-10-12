<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dm6fc8-ju"/><path class="c9elq579y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:database-upload-sharp" {...props}></Icon>
<style>
:global(.c9elq579y) {
  d: path("M4.25 6.25c0 1.95 3.45 3.5 7.75 3.5s7.75-1.55 7.75-3.5M4.25 12c0 1.95 3.45 3.5 7.75 3.5s7.75-1.55 7.75-3.5");
}

:global(.dm6fc8-ju) {
  d: path("M4.25 6.25c0-1.95 3.45-3.5 7.75-3.5s7.75 1.55 7.75 3.5v11.5c0 1.95-3.45 3.5-7.75 3.5s-7.75-1.55-7.75-3.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
