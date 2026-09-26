<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycoe2fbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-right-dashed-panel-sharp" {...props}></Icon>
<style>
:global(.ycoe2fbkk) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 3L14.5 3M21 9.5L21 14.5M3 8L3 3L7 3M17 3L21 3L21 7M16 21L21.0001 21L21 17M2 15.5L13.6757 15.5M7.6757 9.7028L14 15.5L7.7132 21.2628");
}

</style>
