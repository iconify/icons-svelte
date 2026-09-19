<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lf-73mb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blutspende-spenderservice" {...props}></Icon>
<style>
:global(.lf-73mb_u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 17.5h-9a2 2 0 0 1-2-2v-9a1 1 0 0 0-1-1h-11a1 1 0 0 0-1 1v9a2 2 0 0 1-2 2h-9a1 1 0 0 0-1 1v11a1 1 0 0 0 1 1h9a2 2 0 0 1 2 2v9a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1v-9a2 2 0 0 1 2-2h9a1 1 0 0 0 1-1v-11a1 1 0 0 0-1-1");
}

</style>
