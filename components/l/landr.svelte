<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="qkhjthb6w"/><circle class="e2k0bac_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:landr" {...props}></Icon>
<style>
:global(.e2k0bac_g) {
  cx: 27.875px;
  cy: 24px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qkhjthb6w) {
  cx: 20.125px;
  cy: 24px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
