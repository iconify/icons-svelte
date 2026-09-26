<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lielxvqbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:receipt-sharp" {...props}></Icon>
<style>
:global(.lielxvqbd) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9L13 9M7 13L17 13M4 2L20 2L20 20L16 22L12 20L8 22L4 20L4 2Z");
}

</style>
