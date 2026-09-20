<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxis8cwjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:auto-read-pause" {...props}></Icon>
<style>
:global(.yxis8cwjj) {
  fill: currentColor;
  d: path("M9 14h2V6H9zm4 0h2V6h-2zM2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18H6z");
}

</style>
