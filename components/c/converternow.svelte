<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qqp9j_4vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:converternow" {...props}></Icon>
<style>
:global(.qqp9j_4vg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.648 8.722a98.5 98.5 0 0 0-17.937 4.337M43.5 21.776H16.442C2.924 22.109 4.576 33.619 4.552 39.3M36.67 8.7L25.332 19.503m-4.51 4.297L4.552 39.3");
}

</style>
