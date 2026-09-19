<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="hvyrc0bzp"/><circle class="ly61bjbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myim3" {...props}></Icon>
<style>
:global(.hvyrc0bzp) {
  cx: 20.532px;
  cy: 27.468px;
  r: 15.032px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ly61bjbob) {
  cx: 35.982px;
  cy: 12.018px;
  r: 6.518px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
