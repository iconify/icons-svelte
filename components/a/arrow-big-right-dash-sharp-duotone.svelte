<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2ds4tlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-right-dash-sharp-duotone" {...props}></Icon>
<style>
:global(.xi2ds4tlw) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12L14 20L14 16L6 16L6 8L14 8L14 4ZM2 7L2 17");
}

</style>
