<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v2177xb3m"/><path class="vjoucgx_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-curve-left-sharp" {...props}></Icon>
<style>
:global(.v2177xb3m) {
  d: path("M20.25 18.75c0-7.75-3.75-12.25-7.5-12.25s-6 4-6 9.25");
}

:global(.vjoucgx_w) {
  d: path("m2.75 11.75l4 4l4-4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
