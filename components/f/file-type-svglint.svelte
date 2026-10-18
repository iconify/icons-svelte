<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="zgjrod58c"><circle class="izqhagsvm"/><circle class="il595vbpy"/><path class="rl2wnimzx"/><circle class="h2mp_rbdw"/><circle class="hq806s4et"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-svglint" {...props}></Icon>
<style>
:global(.h2mp_rbdw) {
  cx: 12px;
  cy: 19px;
  r: 1.5px;
  fill: var(--svg-color--f5a623, #f5a623);
  stroke: none;
}

:global(.hq806s4et) {
  cx: 20px;
  cy: 19px;
  r: 1.5px;
  fill: var(--svg-color--f5a623, #f5a623);
  stroke: none;
}

:global(.il595vbpy) {
  cx: 16px;
  cy: 16px;
  r: 9.5px;
  stroke-width: var(--svg-stroke-width--3px, 3px);
}

:global(.izqhagsvm) {
  cx: 16px;
  cy: 16px;
  r: 11px;
  stroke-dasharray: 1 1;
  stroke-width: var(--svg-stroke-width--4px, 4px);
}

:global(.rl2wnimzx) {
  stroke-linecap: round;
  d: path("M12 19q4-9 8 0");
}

:global(.zgjrod58c) {
  fill: none;
  stroke: var(--svg-color--f5a623, #f5a623);
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
