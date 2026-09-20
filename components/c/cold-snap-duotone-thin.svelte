<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aq4vrgw8k"/><path class="gnqb99ipa"/><path class="ck_r08b8b"/><path class="fvt2-0orr"/><path class="u4sowhi7h"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cold-snap-duotone-thin" {...props}></Icon>
<style>
:global(.aq4vrgw8k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck_r08b8b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fvt2-0orr) {
  d: path("M12 4v8m-4 0 8 -8");
}

:global(.gnqb99ipa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u4sowhi7h) {
  d: path("M4 16h16");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
