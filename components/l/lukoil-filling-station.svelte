<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kedffpbow"/><path class="gqvlrpbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lukoil-filling-station" {...props}></Icon>
<style>
:global(.gqvlrpbzk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v23.833a4.625 4.625 0 1 1-9.25 0V5.5");
}

:global(.kedffpbow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v33c0 2.216 1.784 4 4 4h33l-9.25-25.084L42.5 5.5");
}

</style>
