<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixw60nbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-header" {...props}></Icon>
<style>
:global(.ixw60nbui) {
  fill: currentColor;
  d: path("M3 5V3h18v2zm16 2q.825 0 1.413.588T21 9v10q0 .825-.587 1.413T19 21H5q-.825 0-1.412-.587T3 19V9q0-.825.588-1.412T5 7z");
}

</style>
