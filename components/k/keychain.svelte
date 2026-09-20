<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qs33xqbmy"/><rect class="xx4_ifb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:keychain" {...props}></Icon>
<style>
:global(.qs33xqbmy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.541 9.713a3.746 3.746 0 1 1 0 7.492a3.746 3.746 0 0 1 0-7.492M13.795 24h20.41m-20.41 6.319h20.41m-20.41 6.319h20.41");
}

:global(.xx4_ifb6u) {
  width: 31px;
  height: 39px;
  x: 8.45px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
