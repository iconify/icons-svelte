<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xlu1wccsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:morse" {...props}></Icon>
<style>
:global(.xlu1wccsn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 34.57A5.56 5.56 0 1 1 15.6 29a5.55 5.55 0 0 1-5.6 5.57m33.39-12.32H21.07v-8.84h22.42Z");
}

</style>
