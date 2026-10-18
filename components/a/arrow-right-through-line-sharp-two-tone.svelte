<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuf0a7bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right-through-line-sharp-two-tone" {...props}></Icon>
<style>
:global(.vuf0a7bbw) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12L21 12M16.7071 7.7071L21 12L16.7071 16.2929M12 2L12 9M12 15L12 22");
}

</style>
