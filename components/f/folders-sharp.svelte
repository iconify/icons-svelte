<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkx4u2t6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folders-sharp" {...props}></Icon>
<style>
:global(.vkx4u2t6n) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9L3 9L3 21L16 21L16 19M8 3L12 3L14 5L21 5L21 16L8 16L8 3Z");
}

</style>
