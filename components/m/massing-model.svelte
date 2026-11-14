<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x92k81_vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:massing-model" {...props}></Icon>
<style>
:global(.x92k81_vx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7h7v13.5H4Zm0 0l3-3h7l-3 3m0 6h7v7.5h-7Zm0 0l3-3h7l-3 3m3-3v7.5l-3 3M14 4v6");
}

</style>
