<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="by7vjkbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-full-fill" {...props}></Icon>
<style>
:global(.by7vjkbvm) {
  fill: currentColor;
  d: path("M208 40v160a16 16 0 0 1-16 16H32a16 16 0 0 1-11.3-27.32l160-160A16 16 0 0 1 208 40");
}

</style>
