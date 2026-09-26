<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af0flxbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-left-sharp" {...props}></Icon>
<style>
:global(.af0flxbxj) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21L3 21L3 5L21 5L21 12M6 11L18 11M8 2L8 8M16 2L16 8M22 18L15 18M18.2929 14.7071L15 18L18.2929 21.2929");
}

</style>
