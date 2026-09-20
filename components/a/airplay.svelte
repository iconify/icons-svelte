<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn3r2_bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:airplay" {...props}></Icon>
<style>
:global(.bn3r2_bye) {
  fill: currentColor;
  d: path("m6 21l6-6l6 6zm-2-2q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v12q0 .825-.587 1.413T20 19h-1l-7-7l-7 7z");
}

</style>
