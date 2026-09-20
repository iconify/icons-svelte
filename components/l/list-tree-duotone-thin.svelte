<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lccp6ubmj"/><path class="sl1xnlz7n"/><path class="eg32wvt_u"/><path class="d31-ss03q"/><path class="uim10mbhy"/><path class="s_qnepbtm"/><path class="e1s2le8fv"/><path class="lmc6jyb6f"/><path class="p41-m0bke"/><path class="vg0qlegui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-tree-duotone-thin" {...props}></Icon>
<style>
:global(.d31-ss03q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e1s2le8fv) {
  d: path("M5 10h6");
}

:global(.eg32wvt_u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lccp6ubmj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 3v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmc6jyb6f) {
  d: path("M14 10h7");
}

:global(.p41-m0bke) {
  d: path("M5 17h6");
}

:global(.s_qnepbtm) {
  d: path("M5 3v14");
}

:global(.sl1xnlz7n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uim10mbhy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vg0qlegui) {
  d: path("M14 17h7");
}

</style>
