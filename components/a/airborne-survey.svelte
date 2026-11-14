<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivq6t_bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:airborne-survey" {...props}></Icon>
<style>
:global(.ivq6t_bpp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.5L3.5 3h2L8 5.5h8.5c2.25 0 4 .75 4 1.5s-1.75 1.5-4 1.5Zm1.5 12l6.5-9l6.5 9m-16 0h19");
}

</style>
