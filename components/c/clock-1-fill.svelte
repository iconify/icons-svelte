<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf12pkbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-1-fill" {...props}></Icon>
<style>
:global(.qf12pkbcc) {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m11-3V7a1 1 0 0 0-2 0v5a1 1 0 0 0 1.8.6l3-4a1 1 0 0 0-1.6-1.2Z");
}

</style>
