<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgc8up6-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:featured-video-sharp" {...props}></Icon>
<style>
:global(.jgc8up6-p) {
  fill: currentColor;
  d: path("M5 14h9V7H5zm-3 6V4h20v16z");
}

</style>
