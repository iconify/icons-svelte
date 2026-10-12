<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbp9_7bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dumbbell-plus-sharp" {...props}></Icon>
<style>
:global(.kbp9_7bic) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 5.25h4v13.5h-4zm10.5 0h4v13.5h-4zM2.75 12h2m14.5 0h2m-12.5 0h6.5");
}

</style>
