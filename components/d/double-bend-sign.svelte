<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpnyvdgai"/><path class="lxkkt6bcp"/><path class="ut88q0tta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:double-bend-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxkkt6bcp) {
  d: path("M11.5 18.75c0-2.75-4-2.5-4-5.25s6.5-2 6.5-5");
}

:global(.tpnyvdgai) {
  d: path("m14.475 4.475l5.05 5.05a3.5 3.5 0 0 1 0 4.95l-5.05 5.05a3.5 3.5 0 0 1-4.95 0l-5.05-5.05a3.5 3.5 0 0 1 0-4.95l5.05-5.05a3.5 3.5 0 0 1 4.95 0");
}

:global(.ut88q0tta) {
  d: path("M12.25 10.25L14 8.5l1.75 1.75");
}

</style>
