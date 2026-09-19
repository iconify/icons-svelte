<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k3rrjlbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rectangle-vertical" {...props}></Icon>
<style>
:global(.k3rrjlbzq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 4.5h-23a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4h23a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4");
}

</style>
