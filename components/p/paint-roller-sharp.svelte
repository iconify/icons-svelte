<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfbpohbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paint-roller-sharp" {...props}></Icon>
<style>
:global(.bfbpohbjg) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 2L18 2L18 9L2 9L2 2ZM11 16L15 16L15 22L11 22L11 16ZM18 5.5L22 5.5L22 13L13 13L13 16");
}

</style>
