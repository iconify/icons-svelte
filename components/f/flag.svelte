<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms4r3gbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flag" {...props}></Icon>
<style>
:global(.ms4r3gbtj) {
  fill: currentColor;
  d: path("M5 21V4h9l.4 2H20v10h-7l-.4-2H7v7z");
}

</style>
