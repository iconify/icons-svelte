<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf4qzpuyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-shortcut" {...props}></Icon>
<style>
:global(.wf4qzpuyi) {
  fill: currentColor;
  d: path("M20.29 10.29L16.7 6.7c-.62-.62-1.7-.18-1.7.71V10H8c-2.76 0-5 2.24-5 5v3c0 .55.45 1 1 1s1-.45 1-1v-3c0-1.65 1.35-3 3-3h7v2.59c0 .89 1.08 1.34 1.71.71l3.59-3.59c.38-.39.38-1.03-.01-1.42");
}

</style>
