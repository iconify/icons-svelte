<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz8d_fbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:line-height-duotone-sharp" {...props}></Icon>
<style>
:global(.jz8d_fbfl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 6h8m-8 6h8m-8 6h8M6 4v16M9 7L6 4L3 7m0 10l3 3l3-3");
}

</style>
