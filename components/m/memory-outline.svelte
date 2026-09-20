<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jch9c8brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:memory-outline" {...props}></Icon>
<style>
:global(.jch9c8brb) {
  fill: currentColor;
  d: path("M9 15V9h6v6zm2-2h2v-2h-2zm-2 8v-2H7q-.825 0-1.412-.587T5 17v-2H3v-2h2v-2H3V9h2V7q0-.825.588-1.412T7 5h2V3h2v2h2V3h2v2h2q.825 0 1.413.588T19 7v2h2v2h-2v2h2v2h-2v2q0 .825-.587 1.413T17 19h-2v2h-2v-2h-2v2zm8-4V7H7v10zm-5-5");
}

</style>
