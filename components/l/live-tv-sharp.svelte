<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn8lzs6fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:live-tv-sharp" {...props}></Icon>
<style>
:global(.wn8lzs6fw) {
  fill: currentColor;
  d: path("M10 14.577L15.577 11L10 7.423zM9 20v-2H3V4h18v14h-6v2z");
}

</style>
