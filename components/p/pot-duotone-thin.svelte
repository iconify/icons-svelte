<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jrq8s6__w"/><path class="yipk7w_dp"/><path class="fh4vasbnq"/><path class="us2evabuy"/><path class="wzsyjh0wp"/><path class="prbp3oa5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pot-duotone-thin" {...props}></Icon>
<style>
:global(.fh4vasbnq) {
  d: path("M8 12a4 4 0 0 1 8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jrq8s6__w) {
  fill: currentColor;
  d: path("M5 12v7h14v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.prbp3oa5j) {
  d: path("M19 15h3");
}

:global(.us2evabuy) {
  d: path("M12 5.5V8");
}

:global(.wzsyjh0wp) {
  d: path("M2 15h3");
}

:global(.yipk7w_dp) {
  d: path("M5 12v7h14v-7Z");
}

</style>
