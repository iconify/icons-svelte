<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcu-0ibeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:fullscreen-exit" {...props}></Icon>
<style>
:global(.mcu-0ibeb) {
  fill: currentColor;
  d: path("M5 16h3v3h2v-5H5zm3-8H5v2h5V5H8zm6 11h2v-3h3v-2h-5zm2-11V5h-2v5h5V8z");
}

</style>
