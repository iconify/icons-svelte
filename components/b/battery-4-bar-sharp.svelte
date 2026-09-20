<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhi03jbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:battery-4-bar-sharp" {...props}></Icon>
<style>
:global(.dhi03jbhp) {
  fill: currentColor;
  d: path("M8.885 12h6.23V5.462h-6.23zm-1 9V4.48h2.423V3h3.384v1.48h2.424V21z");
}

</style>
