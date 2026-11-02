<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixcdw3xng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-right-round" {...props}></Icon>
<style>
:global(.ixcdw3xng) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 13h-3a3 3 0 1 1 3-3za4 4 0 0 1-4 4m-6-4H7a3 3 0 1 1 3-3za4 4 0 0 1-4 4");
}

</style>
