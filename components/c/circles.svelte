<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="y44di6smb"/><circle class="hjrref-js"/><circle class="jmmb2pbah"/><circle class="akq9rggwp"/><circle class="mk0jb2bxt"/><circle class="g60n16bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:circles" {...props}></Icon>
<style>
:global(.akq9rggwp) {
  cx: 35.303px;
  cy: 31.345px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.g60n16bal) {
  cx: 12.697px;
  cy: 24px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hjrref-js) {
  cx: 21.331px;
  cy: 12.115px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jmmb2pbah) {
  cx: 35.303px;
  cy: 16.655px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mk0jb2bxt) {
  cx: 21.331px;
  cy: 35.885px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y44di6smb) {
  cx: 25.193px;
  cy: 24px;
  r: 10.574px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
