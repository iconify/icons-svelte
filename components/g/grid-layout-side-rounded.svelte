<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1odkpgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:grid-layout-side-rounded" {...props}></Icon>
<style>
:global(.wl1odkpgx) {
  fill: currentColor;
  d: path("M21 21V3zM5 21h6q.825 0 1.413-.587T13 19V5q0-.825-.587-1.412T11 3H5q-.825 0-1.412.588T3 5v14q0 .825.588 1.413T5 21m16-2V5q0-.825-.587-1.412T19 3h-2q-.825 0-1.412.588T15 5v14q0 .825.588 1.413T17 21h2q.825 0 1.413-.587T21 19");
}

</style>
