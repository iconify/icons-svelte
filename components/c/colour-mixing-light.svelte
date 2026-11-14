<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l5hr3qb8t"/><path class="dy1yp9btx"/><path class="x2wa61b0h"/><path class="elsl_absx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:colour-mixing-light" {...props}></Icon>
<style>
:global(.dy1yp9btx) {
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.elsl_absx) {
  fill: currentColor;
  d: path("M12 10.75a5.5 5.5 0 0 1 2 3.5a5.5 5.5 0 0 1-4 0a5.5 5.5 0 0 1 2-3.5Z");
}

:global(.l5hr3qb8t) {
  d: path("M6.5 9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x2wa61b0h) {
  d: path("M10 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
