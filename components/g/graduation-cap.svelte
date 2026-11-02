<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yzllbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:graduation-cap" {...props}></Icon>
<style>
:global(.e6yzllbtl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m20 10l-8 4l-8-4l8-4zM8 12v4c0 1.105 1.79 2 4 2s4-.895 4-2v-4m4-2v5");
}

</style>
