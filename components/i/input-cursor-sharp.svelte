<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc24_-13h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:input-cursor-sharp" {...props}></Icon>
<style>
:global(.qc24_-13h) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 7L2 7L2 17L13 17M6 10L6 14M17.9543 17L15.8719 10.8669L22 13.0514L19.4086 14.3063L17.9543 17Z");
}

</style>
