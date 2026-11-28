<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gryy93b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:baseline-sharp" {...props}></Icon>
<style>
:global(.gryy93b2f) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.7402 17.6061L12 3L18.2598 17.6061M7.7131 13L16.2869 13M2 21L22 21");
}

</style>
