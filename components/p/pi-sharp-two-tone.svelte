<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfxqz0b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pi-sharp-two-tone" {...props}></Icon>
<style>
:global(.yfxqz0b0t) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 5L23 5M8 5L8 20M16 5L16 16C16 17.6569 17.3431 19 19 19L20 19");
}

</style>
