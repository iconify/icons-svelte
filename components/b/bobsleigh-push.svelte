<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obeex5_7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bobsleigh-push" {...props}></Icon>
<style>
:global(.obeex5_7b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h10c3.5 0 6 2 6.5 5.5H4Zm1 8.5h8M4 7L2.5 3.5m12.5 15h6m-2.75-2.75L21 18.5l-2.75 2.75");
}

</style>
