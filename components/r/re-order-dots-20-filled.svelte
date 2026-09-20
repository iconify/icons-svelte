<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="ddquyjb-w"/><path class="rg9q3g_gk"/><path class="br8ur4ckw"/><path class="vl7802bms"/><path class="jpq-obbuw"/><path class="pjjym-bdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-dots-20-filled" {...props}></Icon>
<style>
:global(.br8ur4ckw) {
  d: path("M8 14.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0z");
  fill: currentColor;
}

:global(.ddquyjb-w) {
  d: path("M6.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jpq-obbuw) {
  d: path("M15 9.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0z");
  fill: currentColor;
}

:global(.pjjym-bdn) {
  d: path("M13.5 16a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

:global(.rg9q3g_gk) {
  d: path("M6.5 11a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

:global(.vl7802bms) {
  d: path("M13.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3z");
  fill: currentColor;
}

</style>
