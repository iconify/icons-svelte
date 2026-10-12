<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frdod_ufe"/><circle class="p5v-oc_9l"/><path class="k-swvabop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mantel-clock" {...props}></Icon>
<style>
:global(.frdod_ufe) {
  d: path("M5 19.25v-8a7 7 0 0 1 14 0v8Zm-1.75 0h17.5M7 19.25v2m10-2v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-swvabop) {
  d: path("M12 9.25v2l1.25.75");
}

:global(.p5v-oc_9l) {
  cx: 12px;
  cy: 11.25px;
  r: 3.75px;
}

</style>
