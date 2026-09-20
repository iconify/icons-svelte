<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlg9k-bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:restore-from-trash-outline" {...props}></Icon>
<style>
:global(.qlg9k-bnk) {
  fill: currentColor;
  d: path("M11 16h2v-4.15l1.6 1.55L16 12l-4-4l-4 4l1.4 1.4l1.6-1.55zm-4 5q-.825 0-1.412-.587T5 19V6H4V4h5V3h6v1h5v2h-1v13q0 .825-.587 1.413T17 21zM17 6H7v13h10zM7 6v13z");
}

</style>
