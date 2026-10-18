<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flshn6b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-through-line-sharp-two-tone" {...props}></Icon>
<style>
:global(.flshn6b8c) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L12 21M16.2929 16.7071L12 21L7.7071 16.7071M2 12L9 12M15 12L22 12");
}

</style>
