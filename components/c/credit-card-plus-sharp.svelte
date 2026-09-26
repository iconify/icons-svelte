<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apldvfbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-plus-sharp" {...props}></Icon>
<style>
:global(.apldvfbhq) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 10L22 9L22 4L2 4L2 20L12 20L13 20M1 9L2 9L22 9L23 9M19 14V20M16 17H22");
}

</style>
