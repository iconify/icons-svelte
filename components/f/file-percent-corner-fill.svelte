<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-t_fnvre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-percent-corner-fill" {...props}></Icon>
<style>
:global(.b-t_fnvre) {
  fill: currentColor;
  d: path("M11 10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10Zm2-6v2a2 2 0 0 0 2 2h2Zm-1 10a2 2 0 1 1 3.999-.001A2 2 0 0 1 12 14m8.707.707l-6 6a.999.999 0 1 1-1.414-1.414l6-6a.999.999 0 1 1 1.414 1.414M18 20a2 2 0 1 1 3.999-.001A2 2 0 0 1 18 20");
}

</style>
