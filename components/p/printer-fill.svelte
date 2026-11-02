<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca-l0ibtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:printer-fill" {...props}></Icon>
<style>
:global(.ca-l0ibtt) {
  fill: currentColor;
  d: path("M22 9v6a3 3 0 0 1-3 3v1a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-1a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v1a3 3 0 0 1 3 3m-5-4a1 1 0 0 0-1-1H8a.997.997 0 0 0-1 1v1h10Zm-7 5a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Zm-3 8v1a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-1Z");
}

</style>
