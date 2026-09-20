<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8hgg1b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chrome-maximize" {...props}></Icon>
<style>
:global(.n8hgg1b5s) {
  fill: currentColor;
  d: path("M6 20q-.825 0-1.413-.588T4 18V6q0-.825.588-1.413T6 4h12q.825 0 1.413.588T20 6v12q0 .825-.588 1.413T18 20H6Z");
}

</style>
