<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omt9jab7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-play-sharp" {...props}></Icon>
<style>
:global(.omt9jab7v) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3H20M3 7H21V21H3V7ZM9.5 10.38L14.813 14L9.5 17.62V10.38Z");
}

</style>
