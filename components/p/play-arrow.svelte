<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnob25r9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:play-arrow" {...props}></Icon>
<style>
:global(.vnob25r9m) {
  fill: currentColor;
  d: path("M8 5v14l11-7z");
}

</style>
