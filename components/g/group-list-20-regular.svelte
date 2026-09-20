<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yqlwf9wfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:group-list-20-regular" {...props}></Icon>
<style>
:global(.yqlwf9wfu) {
  fill: currentColor;
  d: path("M2.5 3a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H3V4h1.5a.5.5 0 0 0 0-1zm0 8a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H3v-4h1.5a.5.5 0 0 0 0-1zM6 4.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m.5 7.5a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zM6 7.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m.5 7.5a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1z");
}

</style>
