<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-n4kab9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:book-flat-stack" {...props}></Icon>
<style>
:global(.c-n4kab9m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5h18v6H3Zm2-6h15v6H5Zm-1-6h14v6H4Zm2.5 12v6m10-12v6m-9-12v6");
}

</style>
