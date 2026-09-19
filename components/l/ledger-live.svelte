<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r44fjgbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ledger-live" {...props}></Icon>
<style>
:global(.r44fjgbdr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 39.203A21.504 21.504 0 0 1 32.734 4.348m6.469 4.449a21.504 21.504 0 0 1-23.937 34.855m-6.469-4.449l5.657-5.657m19.092-19.092l5.657-5.657");
}

</style>
