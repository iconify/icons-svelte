<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvo27vwut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-left-duocolor-sharp" {...props}></Icon>
<style>
:global(.rvo27vwut) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11h6v6H4za4 4 0 0 1 4-4m6 4h6v6h-6za4 4 0 0 1 4-4");
}

</style>
