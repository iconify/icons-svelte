<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><ellipse class="apk4myb6x"/><ellipse class="nc8qa4b4o"/><ellipse class="e-catjbcd"/><ellipse class="a_faqrbxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:factory-balls" {...props}></Icon>
<style>
:global(.a_faqrbxs) {
  cx: 12.518px;
  cy: 19.877px;
  rx: 3.329px;
  ry: 3.482px;
}

:global(.apk4myb6x) {
  cx: 27.756px;
  cy: 16.136px;
  rx: 8.032px;
  ry: 8.108px;
}

:global(.e-catjbcd) {
  cx: 25.283px;
  cy: 19.969px;
  rx: 3.329px;
  ry: 3.482px;
}

:global(.f_v_dfbgn) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

:global(.nc8qa4b4o) {
  cx: 11.143px;
  cy: 16.686px;
  rx: 6.261px;
  ry: 7.497px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
