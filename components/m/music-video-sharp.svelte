<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgm_dzbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:music-video-sharp" {...props}></Icon>
<style>
:global(.qgm_dzbvg) {
  fill: currentColor;
  d: path("M12.294 15.972q.59-.585.59-1.433V9H15.5V7.462h-3.384v5.5q-.249-.206-.568-.324t-.682-.119q-.849 0-1.434.59q-.586.591-.586 1.43t.59 1.428q.591.59 1.43.59q.838 0 1.428-.585M3 19V5h18v14z");
}

</style>
