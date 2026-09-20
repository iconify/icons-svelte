<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgdv3cfbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-footer" {...props}></Icon>
<style>
:global(.kgdv3cfbu) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm2-4q-.825 0-1.412-.587T3 15V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v10q0 .825-.587 1.413T19 17z");
}

</style>
