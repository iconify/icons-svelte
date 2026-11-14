<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kizc5abrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bobbin" {...props}></Icon>
<style>
:global(.kizc5abrl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h13v3h-13Zm0 16h13v3h-13Zm3-13v13m7-13v13m-7-6.5h7m-7 3h7m-7-6h7c4.5 0 3 5 6 6.5");
}

</style>
