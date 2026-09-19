<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otruaepyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-dehaze" {...props}></Icon>
<style>
:global(.otruaepyy) {
  fill: currentColor;
  d: path("M2 16v2h20v-2zm0-5v2h20v-2zm0-5v2h20V6z");
}

</style>
