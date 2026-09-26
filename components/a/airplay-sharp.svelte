<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi0c9ccqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:airplay-sharp" {...props}></Icon>
<style>
:global(.yi0c9ccqg) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.1043 16L2 16L2 3L22 3L22 16L19.8957 16L18.8957 16M12 13L18 21L6 21L12 13Z");
}

</style>
