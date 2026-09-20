<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ge-1rwbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:f-stop-20-regular" {...props}></Icon>
<style>
:global(.ge-1rwbnu) {
  fill: currentColor;
  d: path("M10.884 5.35a2.833 2.833 0 0 1 3.673-2.216l.788.258a.5.5 0 1 0 .31-.95l-.787-.258a3.833 3.833 0 0 0-4.97 2.997L9.244 9H5.5a.5.5 0 1 0 0 1h3.573l-.622 3.633c-.335 1.96-2.531 2.974-4.24 1.958l-.455-.27a.5.5 0 1 0-.511.859l.455.27c2.312 1.375 5.283.003 5.737-2.648l.65-3.802H13.5a.5.5 0 0 0 0-1h-3.241z");
}

</style>
