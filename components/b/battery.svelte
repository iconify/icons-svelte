<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vnc470bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:battery" {...props}></Icon>
<style>
:global(.vnc470bcb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 4.5h6.67a1 1 0 0 1 1 1v3h4.63a2 2 0 0 1 2 2v31a2 2 0 0 1-2 2H15.19a2 2 0 0 1-2-2v-31a2 2 0 0 1 2-2h4.31v-3a1 1 0 0 1 1-1m-7.31 32H34.8m-15.3-28h8.67");
}

</style>
