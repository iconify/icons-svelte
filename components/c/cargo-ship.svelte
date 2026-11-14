<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja4vp7aru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cargo-ship" {...props}></Icon>
<style>
:global(.ja4vp7aru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15h18l-2.5 5.5h-13Zm2-5.5h4V15H5Zm5 0h4V15h-4Zm5 0h4V15h-4Z");
}

</style>
