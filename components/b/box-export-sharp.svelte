<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqrgcvb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:box-export-sharp" {...props}></Icon>
<style>
:global(.zqrgcvb-u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V6.444l-4.5-2.222m0 0L12 2L3 6.444v11.112L12 22V10.889M3 6.444l9 4.445l9-4.445M18 21l3-3l-3-3m3 3h-6");
}

</style>
