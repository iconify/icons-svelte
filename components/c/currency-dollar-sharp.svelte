<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8jg2bc8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-dollar-sharp" {...props}></Icon>
<style>
:global(.v8jg2bc8j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 8a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v1a3 3 0 0 0 3 3h4a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3m5-13v2m0 14v2");
}

</style>
