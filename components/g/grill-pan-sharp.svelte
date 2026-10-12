<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-_8-yb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:grill-pan-sharp" {...props}></Icon>
<style>
:global(.e-_8-yb7k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6h12.5v12.5H2.75zM6 9.25v6m3-6v6m3-6v6m3.25-6l5.5-5.5");
}

</style>
