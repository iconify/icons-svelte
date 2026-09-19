<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mr75miu3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:beike" {...props}></Icon>
<style>
:global(.mr75miu3y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.565 29.301a15.5 15.5 0 0 1-29.13 0M4.5 24L24 8.5L43.5 24");
}

</style>
