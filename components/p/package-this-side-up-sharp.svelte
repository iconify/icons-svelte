<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p95o4hbbt"/><path class="cdixnqw_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:package-this-side-up-sharp" {...props}></Icon>
<style>
:global(.cdixnqw_i) {
  d: path("M8.75 16.5V8m-2 2l2-2l2 2m4.5 6.5V8m-2 2l2-2l2 2");
}

:global(.p95o4hbbt) {
  d: path("M2.75 3.75h18.5v17.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
