<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rcc46u6dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-right-20-filled" {...props}></Icon>
<style>
:global(.rcc46u6dt) {
  fill: currentColor;
  d: path("M16.5 2a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-1 0v-15a.5.5 0 0 1 .5-.5M13 11a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2zm2-5a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2z");
}

</style>
