<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e16b4dnyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-funnel-sharp-fill" {...props}></Icon>
<style>
:global(.e16b4dnyk) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L3 21L22 21M6 7L22 7M9 12L19 12M12 17L16 17");
}

</style>
