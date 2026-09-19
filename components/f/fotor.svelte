<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wk62geb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fotor" {...props}></Icon>
<style>
:global(.wk62geb3p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5v43M34.75 5.38l-21.5 37.24m29.37-29.37L5.38 34.75M45.5 24h-43m40.12 10.75L5.38 13.25m29.37 29.37L13.25 5.38");
}

</style>
