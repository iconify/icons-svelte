<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtkpawyjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:fullscreen-portrait-outline-sharp" {...props}></Icon>
<style>
:global(.wtkpawyjd) {
  fill: currentColor;
  d: path("M8.385 17.616h7.23V6.385h-7.23zM19 21H5V3h14zm-1-1V4H6v16zm0-16H6z");
}

</style>
