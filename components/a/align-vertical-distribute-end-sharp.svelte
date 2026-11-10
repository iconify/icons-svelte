<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9bt6urym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-vertical-distribute-end-sharp" {...props}></Icon>
<style>
:global(.e9bt6urym) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M23 20H1M23 10H1M16 14V20H8V14H16ZM20 10H4V4H20V10Z");
}

</style>
