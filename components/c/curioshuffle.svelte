<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lym4bor2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:curioshuffle" {...props}></Icon>
<style>
:global(.lym4bor2m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 4.5A5.5 5.5 0 0 0 33 10v25.5a8 8 0 0 1-8 8H9.5A5.5 5.5 0 0 0 15 38V12.5a8 8 0 0 1 8-8z");
}

</style>
