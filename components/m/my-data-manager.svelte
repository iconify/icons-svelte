<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbk0ktbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:my-data-manager" {...props}></Icon>
<style>
:global(.wbk0ktbda) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 26.004h5.266V42.5H10.5zM21.367 5.5h5.266v37h-5.266zm10.867 12.116H37.5V42.5h-5.266z");
}

</style>
