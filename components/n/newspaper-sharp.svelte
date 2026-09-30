<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0zgv8urq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:newspaper-sharp" {...props}></Icon>
<style>
:global(.t0zgv8urq) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 3L21 3L21 21L3 21L3 9L8 9L8 3ZM8 9L8 21M11 8L18 8M11 12L18 12M11 16L16 16");
}

</style>
