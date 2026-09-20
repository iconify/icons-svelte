<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdfg-lpcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobiledata-arrows-outline-sharp" {...props}></Icon>
<style>
:global(.rdfg-lpcu) {
  fill: currentColor;
  d: path("M8 9.975h2v7.175l1.55-1.55L13 17l-4 4l-4-4l1.45-1.4L8 17.15zm8 4h-2V6.8l-1.6 1.6L11 7l4-4l4 4l-1.4 1.4L16 6.8z");
}

</style>
