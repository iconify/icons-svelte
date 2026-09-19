<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mfn55g_je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:markdown" {...props}></Icon>
<style>
:global(.mfn55g_je) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 44.5v-41m17.754 30.75L6.247 13.75m35.507 0L6.247 34.25");
}

</style>
