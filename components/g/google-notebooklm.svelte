<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pjkcywbed"/><path class="xbxeweb2y"/><path class="ciujkkb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:google-notebooklm" {...props}></Icon>
<style>
:global(.ciujkkb0p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 37.664v-7.776c0-10.798 8.73-19.552 19.5-19.552s19.5 8.754 19.5 19.552v7.776");
}

:global(.pjkcywbed) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 37.664c0-5.4 4.365-9.776 9.75-9.776S24 32.265 24 37.664");
}

:global(.xbxeweb2y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 33.776c0-8.099 6.548-14.664 14.625-14.664S33.75 25.677 33.75 33.776v3.888");
}

</style>
