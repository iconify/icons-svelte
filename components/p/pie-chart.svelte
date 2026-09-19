<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wio4a_bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:pie-chart" {...props}></Icon>
<style>
:global(.wio4a_bak) {
  fill: currentColor;
  d: path("M11 2v20c-5.07-.5-9-4.79-9-10s3.93-9.5 9-10m2.03 0v8.99H22c-.47-4.74-4.24-8.52-8.97-8.99m0 11.01V22c4.74-.47 8.5-4.25 8.97-8.99z");
}

</style>
