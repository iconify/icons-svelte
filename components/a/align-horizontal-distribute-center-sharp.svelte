<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg-hp1rhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-horizontal-distribute-center-sharp" {...props}></Icon>
<style>
:global(.tg-hp1rhw) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 17H14V7H17M17 17H20V7H17M17 17V23M17 7V1M7 5H10V19H7M7 5H4V19H7M7 5V1M7 19V23");
}

</style>
