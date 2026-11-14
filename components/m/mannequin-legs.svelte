<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fesv-mbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mannequin-legs" {...props}></Icon>
<style>
:global(.fesv-mbxx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.5h11l-1 13H14L13 10h-2l-1 7.5H7.5ZM12 10v11.5m-3.5 0h7m-9-14h11");
}

</style>
