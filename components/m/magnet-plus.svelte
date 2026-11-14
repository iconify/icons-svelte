<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nygideyot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:magnet-plus" {...props}></Icon>
<style>
:global(.nygideyot) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15V9a5.75 5.75 0 0 1 11.5 0v6h-3.75V9a2 2 0 0 0-4 0v6Zm0-2.75h3.75m4 0h3.75M18 15v6m-3-3h6");
}

</style>
