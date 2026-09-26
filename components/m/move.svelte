<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khn9nwoel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:move" {...props}></Icon>
<style>
:global(.khn9nwoel) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12L2 12M5 15L2 12L5 9M15 12L22 12M19 9L22 12L19 15M12 9L12 2M9 5L12 2L15 5M12 15L12 22M15 19L12 22L9 19");
}

</style>
