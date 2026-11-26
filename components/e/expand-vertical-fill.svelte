<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5x-bfb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-vertical-fill" {...props}></Icon>
<style>
:global(.x5x-bfb_w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 2L19 2M5 22L19 22M12 6L12 18M9 9L12 6L15 9M9 15L12 18L15 15");
}

</style>
