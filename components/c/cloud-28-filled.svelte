<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="dboq9ubmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cloud-28-filled" {...props}></Icon>
<style>
:global(.dboq9ubmq) {
  fill: currentColor;
  d: path("M14 5a7 7 0 0 0-6.931 6.017A5.5 5.5 0 0 0 7.5 22h13a5.5 5.5 0 0 0 .431-10.983A7 7 0 0 0 14 5");
}

</style>
