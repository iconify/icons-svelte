<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ho87bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-off-sharp" {...props}></Icon>
<style>
:global(.i3ho87bet) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5c-1.458.615-3 1.615-3 4c0 6 9 11 9 11s2.556-1.653 5-4m3-3c.703-1.2 1-2.653 1-4c0-5.34-5.37-5.754-8-3M3 2l19 19");
}

</style>
