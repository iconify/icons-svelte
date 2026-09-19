<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cxfr3tyys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:doubletwistpro" {...props}></Icon>
<style>
:global(.cxfr3tyys) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.578 22.255l13.948-6.803L24 4.5v39L6.474 32.548l13.948-6.803");
}

</style>
