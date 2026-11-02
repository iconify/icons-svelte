<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoena0bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-11-fill-sharp" {...props}></Icon>
<style>
:global(.eoena0bol) {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m11 0V7a1 1 0 0 0-2 0v2L9.8 7.4a1 1 0 0 0-1.6 1.2l3 4A1 1 0 0 0 13 12");
}

</style>
