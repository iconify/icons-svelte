<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m78aqsbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:check-box-outline-sharp" {...props}></Icon>
<style>
:global(.m78aqsbah) {
  fill: currentColor;
  d: path("m10.6 16.2l7.05-7.05l-1.4-1.4l-5.65 5.65l-2.85-2.85l-1.4 1.4zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
