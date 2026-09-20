<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="qpeayrb0a"/><path class="sxqsyib9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:reciept-20-regular" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.qpeayrb0a) {
  d: path("M3 5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v7h3v2a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V5zm11 8v3a2 2 0 0 0 2-2v-1h-2zm-1 3V5a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v9a2 2 0 0 0 2 2h7z");
  fill: currentColor;
}

:global(.sxqsyib9m) {
  d: path("M6 6.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5zm0 3a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5zm0 3a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5z");
  fill: currentColor;
}

</style>
