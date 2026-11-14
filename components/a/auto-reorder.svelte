<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="efm-cmbhw"/><path class="wjoobkbtd"/><path class="k2kp2g75r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:auto-reorder" {...props}></Icon>
<style>
:global(.efm-cmbhw) {
  d: path("M9.541 21.176A9.5 9.5 0 0 1 7.985 3.39m6.474-.566a9.5 9.5 0 0 1 1.556 17.786");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2kp2g75r) {
  d: path("M7.25 9.25L12 12l4.75-2.75M12 12v5.5");
}

:global(.wjoobkbtd) {
  d: path("M21.5 5.25L20.5 8l-2.75-1M2.5 18.75l1-2.75l2.75 1m6.502-10.065l3.25 1.882a1.5 1.5 0 0 1 .748 1.298v3.77a1.5 1.5 0 0 1-.748 1.298l-3.25 1.882a1.5 1.5 0 0 1-1.504 0l-3.25-1.882a1.5 1.5 0 0 1-.748-1.298v-3.77a1.5 1.5 0 0 1 .748-1.298l3.25-1.882a1.5 1.5 0 0 1 1.504 0");
}

</style>
