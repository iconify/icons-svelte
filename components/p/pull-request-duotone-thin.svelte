<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qecovn3xi"/><path class="st2iv5bfu"/><path class="doj56ib_s"/><path class="fsal-c_tf"/><path class="dwa-v92dh"/><path class="kn0tcm93r"/><path class="xaitxdbcw"/><path class="brze8vkpt"/><path class="pw61xnbei"/><path class="e3ixvub0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pull-request-duotone-thin" {...props}></Icon>
<style>
:global(.brze8vkpt) {
  d: path("M18 5v11.5");
}

:global(.doj56ib_s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7.5V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dwa-v92dh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e3ixvub0q) {
  d: path("m15 8 3 -3 3 3");
}

:global(.fsal-c_tf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v11.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kn0tcm93r) {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.pw61xnbei) {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qecovn3xi) {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.st2iv5bfu) {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xaitxdbcw) {
  d: path("M6 7.5V21");
}

</style>
