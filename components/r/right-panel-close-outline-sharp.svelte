<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1w1-vy1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:right-panel-close-outline-sharp" {...props}></Icon>
<style>
:global(.b1w1-vy1m) {
  fill: currentColor;
  d: path("m7.5 16l4-4l-4-4zm8.5 3h3V5h-3zM5 19h9V5H5zm11 0h3zM3 21V3h18v18z");
}

</style>
