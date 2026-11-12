<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="prbf6mb6m"/><path class="c65obhuad"/><path class="lxnzn9nmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:receive-square-line-duotone" {...props}></Icon>
<style>
:global(.c65obhuad) {
  d: path("M17 16L17 12L17 8");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxnzn9nmw) {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.prbf6mb6m) {
  stroke-linejoin: round;
  d: path("M7 12L14 12M11 9L14 12L11 15");
}

</style>
