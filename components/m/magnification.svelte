<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpbi5utgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magnification" {...props}></Icon>
<style>
:global(.fpbi5utgk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm10.25 4.25l5.25 5.25m0-17.5v5M16 5.5h5");
}

</style>
