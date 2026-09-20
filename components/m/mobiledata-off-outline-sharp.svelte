<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmtir0bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mobiledata-off-outline-sharp" {...props}></Icon>
<style>
:global(.wmtir0bpn) {
  fill: currentColor;
  d: path("M19.8 22.6L10 12.8v4.35l1.55-1.55L13 17l-4 4l-4-4l1.45-1.4L8 17.15V10.8L1.4 4.2l1.4-1.4l18.4 18.4zM16 13.15l-2-2V6.8l-1.6 1.6L11 7l4-4l4 4l-1.4 1.4L16 6.8z");
}

</style>
