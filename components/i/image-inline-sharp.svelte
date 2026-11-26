<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggn6-6buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-inline-sharp" {...props}></Icon>
<style>
:global(.ggn6-6buc) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9L15 9L15 15L9 15ZM2 3L22 3M2 21L22 21M2 12L6 12M18 12L22 12");
}

</style>
