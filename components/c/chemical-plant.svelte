<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt-atfj3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chemical-plant" {...props}></Icon>
<style>
:global(.pt-atfj3j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21V7a3.5 3.5 0 0 1 7 0v14m3 0V10a3.5 3.5 0 0 1 7 0v11m-18 0h19m-11-7h3");
}

</style>
