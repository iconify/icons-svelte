<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="bdxedv3gx"/><path class="i4nkkkbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exam-timer-outline-thin" {...props}></Icon>
<style>
:global(.bdxedv3gx) {
  d: path("M6 3v3l6 6 6 -6V3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4nkkkbsh) {
  d: path("M6 21v-3l6 -6 6 6v3");
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
