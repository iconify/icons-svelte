<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz3pr3bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mouse-pointer-sharp-duotone" {...props}></Icon>
<style>
:global(.vz3pr3bvt) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 9.2011L15.008 12.1796L21 18.5858L18.5858 21L12.2249 15.0533L8.9427 21Z");
}

</style>
