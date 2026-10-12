<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo7g4vbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chevron-down-right-sharp" {...props}></Icon>
<style>
:global(.xo7g4vbxw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8.25h14.542L18.7 9.95l-6 5.6l-.7.686l-.7-.686l-6-5.6l-1.842-1.7z");
}

</style>
