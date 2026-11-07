<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2ggchb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-zap-sharp" {...props}></Icon>
<style>
:global(.b2ggchb_y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h10v10H3zm3-4v4m4-4v4M8 17v4M20 7l-3 5h4l-3 5");
}

</style>
