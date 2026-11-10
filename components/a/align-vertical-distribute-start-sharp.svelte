<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so59oyb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-vertical-distribute-start-sharp" {...props}></Icon>
<style>
:global(.so59oyb5k) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M23 4H1M23 14H1M16 10V4H8V10H16ZM20 14H4V20H20V14Z");
}

</style>
