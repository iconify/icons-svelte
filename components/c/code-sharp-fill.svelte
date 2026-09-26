<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smcqkob_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:code-sharp-fill" {...props}></Icon>
<style>
:global(.smcqkob_w) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.2993 4.6508L2 12L8.2993 19.3492M15.7007 4.6508L22 12L15.7007 19.3492");
}

</style>
