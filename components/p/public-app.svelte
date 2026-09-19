<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="q9icox8la"/><circle class="s50phcb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:public-app" {...props}></Icon>
<style>
:global(.q9icox8la) {
  cx: 18.339px;
  cy: 37.839px;
  r: 5.661px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s50phcb6d) {
  cx: 24px;
  cy: 16.452px;
  r: 11.952px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
