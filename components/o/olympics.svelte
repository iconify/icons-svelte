<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="l13rasbzw"/><circle class="b2s6wemss"/><circle class="q38a0zbfy"/><circle class="swc4tonsc"/><circle class="bo1ha4bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:olympics" {...props}></Icon>
<style>
:global(.b2s6wemss) {
  cx: 24px;
  cy: 20.832px;
  r: 5.816px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.bo1ha4bli) {
  cx: 30.842px;
  cy: 27.168px;
  r: 5.816px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.l13rasbzw) {
  cx: 10.316px;
  cy: 20.832px;
  r: 5.816px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q38a0zbfy) {
  cx: 37.684px;
  cy: 20.832px;
  r: 5.816px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.swc4tonsc) {
  cx: 17.158px;
  cy: 27.168px;
  r: 5.816px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
