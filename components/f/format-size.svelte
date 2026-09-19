<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxms23bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:format-size" {...props}></Icon>
<style>
:global(.uxms23bbn) {
  fill: currentColor;
  d: path("M9 4v3h5v12h3V7h5V4zm-6 8h3v7h3v-7h3V9H3z");
}

</style>
