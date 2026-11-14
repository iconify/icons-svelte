<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb1t167ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bridge-arch" {...props}></Icon>
<style>
:global(.cb1t167ha) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v10h-3a6.5 6.5 0 0 0-13 0h-3Zm0 14.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
