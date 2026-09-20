<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlj37ccdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:iframe-outline" {...props}></Icon>
<style>
:global(.mlj37ccdw) {
  fill: currentColor;
  d: path("M11.5 13.5h5v-2h-5zM10 15v-5h8v5zm-6 5q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V8H4z");
}

</style>
