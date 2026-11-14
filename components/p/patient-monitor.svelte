<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkzbbowvf"/><path class="s2o1_jbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:patient-monitor" {...props}></Icon>
<style>
:global(.fkzbbowvf) {
  d: path("M7 3.5h10A3.5 3.5 0 0 1 20.5 7v4a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 11V7A3.5 3.5 0 0 1 7 3.5m5 11V18m-5 3h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s2o1_jbxy) {
  d: path("M6 9h2l1.25-2.25l1.75 4.5L12 9m3-2h3m-3 4h3");
}

</style>
