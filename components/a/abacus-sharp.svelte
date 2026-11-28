<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r00d68pci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:abacus-sharp" {...props}></Icon>
<style>
:global(.r00d68pci) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 2L5 21M19 2L19 21M2 21L22 21M5 8L19 8M5 15L19 15M9 5.5L9 10.5M13 5.5L13 10.5M11 12.5L11 17.5M15 12.5L15 17.5");
}

</style>
