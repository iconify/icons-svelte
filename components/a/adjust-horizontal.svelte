<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op4ut9b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:adjust-horizontal" {...props}></Icon>
<style>
:global(.op4ut9b5j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8H11m8 0h1.5M13 5h4v6h-4ZM3.5 16H5m8 0h7.5M7 13h4v6H7Z");
}

</style>
