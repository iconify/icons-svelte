<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h_hgy3b5i"/><path class="cdj0hjb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:genskill" {...props}></Icon>
<style>
:global(.cdj0hjb9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.925 30.52l26.15-.063L23.968 43.5L10.925 30.521");
}

:global(.h_hgy3b5i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.925 4.563v25.958L37.075 4.5v25.957z");
}

</style>
