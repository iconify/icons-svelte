<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qygeugb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-fill-sharp" {...props}></Icon>
<style>
:global(.qygeugb9o) {
  fill: currentColor;
  d: path("M5 20V3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v17h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm9.01-9H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
