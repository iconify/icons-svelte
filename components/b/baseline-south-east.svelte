<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1t-4526n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-south-east" {...props}></Icon>
<style>
:global(.i1t-4526n) {
  fill: currentColor;
  d: path("M19 9h-2v6.59L5.41 4L4 5.41L15.59 17H9v2h10z");
}

</style>
