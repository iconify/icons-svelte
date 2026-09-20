<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0rbhee_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-0-bar-outline-sharp" {...props}></Icon>
<style>
:global(.y0rbhee_v) {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18zm2-2h6V6H9z");
}

</style>
