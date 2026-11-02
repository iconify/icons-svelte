<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yizhzcf5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eyedropper" {...props}></Icon>
<style>
:global(.yizhzcf5j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 13l-5 5l-5 2l2-5l5-5M9 8l7 7m-2-2l1 1l4-4a3.536 3.536 0 0 0-5-5l-4 4l1 1");
}

</style>
