<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5xuvkbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:detector-offline-sharp" {...props}></Icon>
<style>
:global(.x5xuvkbow) {
  fill: currentColor;
  d: path("M9.4 21L8 19.6l2.6-2.6L8 14.4L9.4 13l2.6 2.6l2.6-2.6l1.4 1.4l-2.6 2.6l2.6 2.6l-1.4 1.4l-2.6-2.6zM8.1 8l.3 1h7.2l.3-1zm-1.15 3L6 8H3V3h18v5h-3l-1.15 3z");
}

</style>
