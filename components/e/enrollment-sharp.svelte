<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cv8ppccvb"/><path class="u1arpkkvg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:enrollment-sharp" {...props}></Icon>
<style>
:global(.cv8ppccvb) {
  d: path("m12.17 3.58l7.41 3.59l.67.33l-.67.33l-7.41 3.59l-.67.33l-.67-.33l-7.41-3.59l-.67-.33l.67-.33l7.41-3.59l.67-.33z");
}

:global(.u1arpkkvg) {
  d: path("M6.5 9.32v4.18c3 2 7 2 10 0V9.32m2 6.68v5.25m-2.62-2.62h5.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
