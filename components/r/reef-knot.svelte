<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lq4uw6riw"/><path class="gqz5ks03w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reef-knot" {...props}></Icon>
<style>
:global(.gqz5ks03w) {
  d: path("M21.5 10H12a4 4 0 0 0 0 8h9.5");
}

:global(.lq4uw6riw) {
  d: path("M2.5 6H12a4 4 0 0 1 0 8H2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
