<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fohtfpfqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-2-plus-sharp" {...props}></Icon>
<style>
:global(.fohtfpfqi) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3L2 3L2 17L22 17L22 12M12 17L12 21M7 21L17 21M19 2L19 10M15 6L23 6");
}

</style>
