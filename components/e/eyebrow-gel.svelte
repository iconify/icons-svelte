<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdga1rbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eyebrow-gel" {...props}></Icon>
<style>
:global(.kdga1rbvr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 6h5v15.5h-5ZM5 15h5v6.5H5Zm2.5 0v-3.5l-2.25-1.25l4.5-1.5l-4.5-1.5l4.5-1.5l-4.5-1.5L7.5 3");
}

</style>
