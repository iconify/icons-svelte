<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs9ndob3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-horizontal-distribute-start-sharp" {...props}></Icon>
<style>
:global(.rs9ndob3v) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 1V23M14 1V23M20 8H14V16H20V8ZM4 4V20H10V4H4Z");
}

</style>
