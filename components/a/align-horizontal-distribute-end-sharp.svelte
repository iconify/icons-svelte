<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owc2yro2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-horizontal-distribute-end-sharp" {...props}></Icon>
<style>
:global(.owc2yro2w) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 1V23M10 1V23M4 8H10V16H4V8ZM20 4V20H14V4H20Z");
}

</style>
