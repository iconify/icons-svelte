<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<g class="ft5dv1b6b"><path class="gem-7_hbl"/><path class="hsu5-f7ew"/><path class="l6adibbeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-28-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gem-7_hbl) {
  d: path("M8.751 14a2.75 2.75 0 1 1-5.5 0a2.75 2.75 0 0 1 5.5 0z");
  fill: currentColor;
}

:global(.hsu5-f7ew) {
  d: path("M16.751 14a2.75 2.75 0 1 1-5.5 0a2.75 2.75 0 0 1 5.5 0z");
  fill: currentColor;
}

:global(.l6adibbeh) {
  d: path("M22.001 16.75a2.75 2.75 0 1 0 0-5.5a2.75 2.75 0 0 0 0 5.5z");
  fill: currentColor;
}

</style>
