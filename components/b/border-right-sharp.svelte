<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk4_xbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:border-right-sharp" {...props}></Icon>
<style>
:global(.mlk4_xbpz) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 3L21 3L21 21L17 21M3 7L3 3L7 3M9.5 3L14.5 3M14.5 21L9.5 21M7 21L3 21L3 17M3 14.5L3 9.5");
}

</style>
