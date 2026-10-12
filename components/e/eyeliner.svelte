<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srzo4dbvh"/><circle class="ivjch5bsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eyeliner" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivjch5bsa) {
  cx: 10.15px;
  cy: 14px;
  r: 2.25px;
}

:global(.srzo4dbvh) {
  d: path("M2.75 14c2.2 3.2 4.9 4.75 7.4 4.75s5.2-1.55 7.35-4.75M2.75 14c2.2-3.2 4.9-4.75 7.4-4.75s5.2 1.55 7.35 4.75l3.75-3.75");
}

</style>
