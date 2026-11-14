<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3srmzbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:football-american-laces" {...props}></Icon>
<style>
:global(.d3srmzbgk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12C6 5 18 5 21.5 12C18 19 6 19 2.5 12Zm5 0h9M9 10v4m3-4v4m3-4v4");
}

</style>
