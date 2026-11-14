<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d_dr_3b-h"/><path class="kda73cczc"/><path class="voktf9o_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eye-patch" {...props}></Icon>
<style>
:global(.d_dr_3b-h) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M3 8l18-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kda73cczc) {
  fill: currentColor;
  d: path("M5.75 10.75a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0");
}

:global(.voktf9o_r) {
  d: path("M15.5 10.75h.01M9.5 16.5h5");
}

</style>
