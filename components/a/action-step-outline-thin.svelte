<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5r_prbgx"/><path class="pc79hvbyu"/><path class="kp327jbpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:action-step-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kp327jbpy) {
  d: path("M20 16.5V20h-3.5");
}

:global(.o5r_prbgx) {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pc79hvbyu) {
  d: path("M9.5 9.5 16 16");
}

</style>
