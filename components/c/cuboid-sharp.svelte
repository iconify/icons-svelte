<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bag1n_9lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cuboid-sharp" {...props}></Icon>
<style>
:global(.bag1n_9lm) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8L8 3L21 3L21 16L16 21L3 21ZM3 8L16 8L16 21M16 8L21 3");
}

</style>
