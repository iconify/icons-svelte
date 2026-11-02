<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri0xb9b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-right-fill-round" {...props}></Icon>
<style>
:global(.ri0xb9b2d) {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m10.293 2.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414l-3-3a.999.999 0 1 0-1.414 1.414L13.586 11H8a1 1 0 0 0 0 2h5.586Z");
}

</style>
