<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vp1_ujbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lessscreen" {...props}></Icon>
<style>
:global(.vp1_ujbol) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.77 4.5h20.46a4 4 0 0 1 4 4v31a4 4 0 0 1-4 4H13.77a4 4 0 0 1-4-4v-31a4 4 0 0 1 4-4m3.906 6.812h12.648");
}

</style>
