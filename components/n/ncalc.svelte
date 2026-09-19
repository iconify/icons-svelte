<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g8eofqbbm"/><circle class="wee0kgadd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ncalc" {...props}></Icon>
<style>
:global(.g8eofqbbm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.232 4.5v14.053m7.027-7.026H26.206M12.838 33.784V17.977a1 1 0 0 1 1.708-.706l16.978 17.053a1 1 0 0 0 1.708-.705V21.895");
}

:global(.wee0kgadd) {
  cx: 12.838px;
  cy: 38.642px;
  r: 4.858px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
