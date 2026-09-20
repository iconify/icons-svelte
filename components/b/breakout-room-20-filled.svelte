<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cb48ujbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:breakout-room-20-filled" {...props}></Icon>
<style>
:global(.cb48ujbge) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-3.354A4 4 0 0 0 12 14v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-3 1.354zm3 3a3 3 0 0 0-3 3v2a3 3 0 0 0 3 3h2a3 3 0 0 0 3-3v-2a3 3 0 0 0-3-3z");
}

</style>
