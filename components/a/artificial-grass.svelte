<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyx-ai0xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:artificial-grass" {...props}></Icon>
<style>
:global(.vyx-ai0xo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v5.5h-19ZM4 13l2-7.5L8 13l2-7.5l2 7.5l2-7.5l2 7.5l2-7.5l2 7.5");
}

</style>
