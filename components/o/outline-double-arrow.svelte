<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw6235bcd"/><path class="h6i3--k-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-double-arrow" {...props}></Icon>
<style>
:global(.h6i3--k-y) {
  fill: currentColor;
  d: path("M8.5 5H4l5 7l-5 7h4.5l5-7z");
}

:global(.yw6235bcd) {
  fill: currentColor;
  d: path("M15.5 5H11l5 7l-5 7h4.5l5-7z");
}

</style>
