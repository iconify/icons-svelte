<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kluly4b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bookmark-check-sharp" {...props}></Icon>
<style>
:global(.kluly4b3d) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 2L20 2L20 22L12 18.4223L4 22L4 2ZM8.7071 10.2071L11 12.5L15.2929 8.2071");
}

</style>
