<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmgozgbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:padland" {...props}></Icon>
<style>
:global(.hmgozgbuo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 42.5L5.5 30.366V5.5l9.25 12.134zm9.25 0l-9.25-12.134V5.5L24 17.634zm9.25 0L24 30.366V5.5l9.25 12.134zm9.25 0l-9.25-12.134V5.5l9.25 12.134z");
}

</style>
