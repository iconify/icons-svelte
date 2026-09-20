<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4lix-bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:music-note-outline" {...props}></Icon>
<style>
:global(.b4lix-bbx) {
  fill: currentColor;
  d: path("M7.175 19.825Q6 18.65 6 17t1.175-2.825T10 13q.575 0 1.063.138t.937.412V3h6v4h-4v10q0 1.65-1.175 2.825T10 21t-2.825-1.175");
}

</style>
