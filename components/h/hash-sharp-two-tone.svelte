<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsjxj3b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hash-sharp-two-tone" {...props}></Icon>
<style>
:global(.dsjxj3b2o) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 8.5L22 8.5M2 15.5L22 15.5M7.4012 21.8896L9.5988 2.1104M14.4012 21.8896L16.5988 2.1104");
}

</style>
