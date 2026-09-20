<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqk-9nlij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chat-bubble-off-outline-sharp" {...props}></Icon>
<style>
:global(.qqk-9nlij) {
  fill: currentColor;
  d: path("M20 18V4H6.85l-2-2H22v16zm.5 5.3L15.15 18H6l-4 4V4.8L.7 3.5l1.4-1.4l19.8 19.8zM4 6.8V18l2-2h7.2z");
}

</style>
