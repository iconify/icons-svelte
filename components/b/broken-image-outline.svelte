<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brgxy0igi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:broken-image-outline" {...props}></Icon>
<style>
:global(.brgxy0igi) {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm1-8.425l4-4l4 4l4-4l1 1V5H5v6.575zM5 19h14v-6.6l-1-1l-4 4l-4-4l-4 4l-1-1zm0 0v-6.6v2V5z");
}

</style>
