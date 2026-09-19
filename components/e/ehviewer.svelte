<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="too6ovb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ehviewer" {...props}></Icon>
<style>
:global(.too6ovb8o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.77 42.5H7.16v-37h18.5m0 9.504V42.5M7.16 24h33.68v18.5");
}

</style>
