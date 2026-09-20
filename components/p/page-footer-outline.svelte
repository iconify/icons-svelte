<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6875141n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-footer-outline" {...props}></Icon>
<style>
:global(.w6875141n) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm2-4q-.825 0-1.412-.587T3 15V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v10q0 .825-.587 1.413T19 17zm0-2h14V5H5zm0 0V5z");
}

</style>
