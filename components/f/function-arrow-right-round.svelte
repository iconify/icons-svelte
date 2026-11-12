<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqumwfbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:function-arrow-right-round" {...props}></Icon>
<style>
:global(.mqumwfbmh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 4c-3 0-3 0-4 4l-2 8c-1 4-1 4-4 4m2-10h7m1 4h8m-3-3l3 3l-3 3");
}

</style>
