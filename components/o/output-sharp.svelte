<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-k8lbcfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:output-sharp" {...props}></Icon>
<style>
:global(.n-k8lbcfs) {
  fill: currentColor;
  d: path("M3 21V3h18v4h-2V5H5v14h14v-2h2v4zm14-4l-1.4-1.4l2.575-2.6H9v-2h9.175L15.6 8.4L17 7l5 5z");
}

</style>
