<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsobnkbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-open-sharp" {...props}></Icon>
<style>
:global(.hsobnkbit) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.7236 15.5528L8 11L22 11L19.0753 20L2 20L2 4L8 4L10 6L19 6L19 12");
}

</style>
