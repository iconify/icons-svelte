<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrdx0_b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:barbell-loaded" {...props}></Icon>
<style>
:global(.qrdx0_b-l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h3.5v12H3Zm3.5 2h3v8h-3Zm11-2H21v12h-3.5Zm-3 2h3v8h-3Zm-5 4h5");
}

</style>
