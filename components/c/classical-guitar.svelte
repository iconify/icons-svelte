<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zviyn4w0j"/><path class="atmpekb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:classical-guitar" {...props}></Icon>
<style>
:global(.atmpekb0l) {
  d: path("M10.75 17.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zviyn4w0j) {
  d: path("M10 14.5a2.5 2.5 0 1 1 4 0a3.75 3.75 0 1 1-4 0Zm2-4V6m-1.25-3.5h2.5V6h-2.5Z");
}

</style>
