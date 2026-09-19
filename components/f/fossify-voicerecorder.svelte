<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n8fjadbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fossify-voicerecorder" {...props}></Icon>
<style>
:global(.n8fjadbaz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v37m-8.224-28.71v20.42m16.448-20.42v20.42M7.552 21.901v4.02m32.896-4.02v4.02");
}

</style>
