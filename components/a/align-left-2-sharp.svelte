<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn__r1bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-left-2-sharp" {...props}></Icon>
<style>
:global(.wn__r1bqv) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L3 22M7 4.5L22 4.5M7 9.5L22 9.5M7 14.5L19 14.5M7 19.5L15 19.5");
}

</style>
