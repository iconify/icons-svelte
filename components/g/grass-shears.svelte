<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8blemb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grass-shears" {...props}></Icon>
<style>
:global(.v8blemb2b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.25 7L21 18.5M11 5.75L18.5 21");
}

</style>
