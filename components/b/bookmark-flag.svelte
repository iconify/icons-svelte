<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a77bityce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bookmark-flag" {...props}></Icon>
<style>
:global(.a77bityce) {
  fill: currentColor;
  d: path("M9.5 14H11v-3h4.5L14 9l1.5-2h-6zM5 21V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v16l-7-3z");
}

</style>
