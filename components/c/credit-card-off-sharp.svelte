<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2vwclswm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-off-sharp" {...props}></Icon>
<style>
:global(.w2vwclswm) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 9L9 9M13.6569 9L14.6569 9L22 9M20 20L2 20L2 4L4 4M8.6569 4L9.6569 4L22 4L22 16.3431L22 17.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
