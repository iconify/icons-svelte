<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f1yfyy14d"/><circle class="cjb7gmbqn"/><circle class="chmopnomt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-bubble-chart" {...props}></Icon>
<style>
:global(.chmopnomt) {
  cx: 15.2px;
  cy: 8.8px;
  r: 4.8px;
  fill: currentColor;
}

:global(.cjb7gmbqn) {
  cx: 14.8px;
  cy: 18px;
  r: 2px;
  fill: currentColor;
}

:global(.f1yfyy14d) {
  cx: 7.2px;
  cy: 14.4px;
  r: 3.2px;
  fill: currentColor;
}

</style>
