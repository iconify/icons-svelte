<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjfc0s6ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mountain" {...props}></Icon>
<style>
:global(.jjfc0s6ef) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l2-4a1.118 1.118 0 0 1 2 0l1 2a1.118 1.118 0 0 0 2 0a1.118 1.118 0 0 1 2 0l4 8c.46.919-.081 2-1 2H5c-.919 0-1.46-1.081-1-2z");
}

</style>
