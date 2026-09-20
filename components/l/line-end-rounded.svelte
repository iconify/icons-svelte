<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr7w-kbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:line-end-rounded" {...props}></Icon>
<style>
:global(.fr7w-kbzi) {
  fill: currentColor;
  d: path("M19.5 14q-.698 0-1.237-.425t-.698-1.075H3q-.213 0-.356-.144t-.144-.357t.144-.356T3 11.5h14.566q.159-.65.698-1.075T19.5 10q.84 0 1.42.58t.58 1.419t-.58 1.42T19.5 14");
}

</style>
