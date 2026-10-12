<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnggm9bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:move-vertical-sharp-fill" {...props}></Icon>
<style>
:global(.dnggm9bcb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21L12 3M7.7071 7.2929L12 3L16.2929 7.2929M7.7071 16.7071L12 21L16.2929 16.7071");
}

</style>
