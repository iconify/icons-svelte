<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdthv3bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:maximize-rounded" {...props}></Icon>
<style>
:global(.tdthv3bcv) {
  fill: currentColor;
  d: path("M5.5 5q-.213 0-.356-.144T5 4.499t.144-.356T5.5 4h13q.213 0 .356.144t.144.357t-.144.356T18.5 5z");
}

</style>
