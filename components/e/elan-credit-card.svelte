<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oq9_psbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:elan-credit-card" {...props}></Icon>
<style>
:global(.oq9_psbzb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v27.75a9.23 9.23 0 0 0 9.25 9.25H42.5M24 5.5h18.5V24");
}

</style>
