<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pm8fpccke"/><circle class="o-_1o3beq"/><circle class="ou244bblc"/><circle class="u38whcbki"/><circle class="dt7y3rbea"/><circle class="jcxm0gmcx"/><circle class="fbp8fgpqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boardroom" {...props}></Icon>
<style>
:global(.dt7y3rbea) {
  cx: 6.5px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.fbp8fgpqp) {
  cx: 17.5px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jcxm0gmcx) {
  cx: 12px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.o-_1o3beq) {
  cx: 6.5px;
  cy: 4.5px;
  r: 1.25px;
}

:global(.ou244bblc) {
  cx: 12px;
  cy: 4.5px;
  r: 1.25px;
}

:global(.pm8fpccke) {
  width: 16.5px;
  height: 5.5px;
  x: 3.75px;
  y: 9.25px;
  rx: 2.25px;
}

:global(.u38whcbki) {
  cx: 17.5px;
  cy: 4.5px;
  r: 1.25px;
}

</style>
