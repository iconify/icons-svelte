<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hqd25e92l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:enki" {...props}></Icon>
<style>
:global(.hqd25e92l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.337 21.878L4.5 25.592l5.837 3.714m27.326-7.428l5.837 3.714l-5.837 3.714m-8.224 3.184l5.837-16.98M24.728 29.07a4.96 4.96 0 0 1-4.31 2.502h0a4.96 4.96 0 0 1-4.96-4.96v-3.224a4.96 4.96 0 0 1 4.96-4.96h0a4.96 4.96 0 0 1 4.96 4.96V25h-9.92");
}

</style>
