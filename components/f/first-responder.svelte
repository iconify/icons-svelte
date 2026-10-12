<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lpws5cv_a"/><path class="oj484ac2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:first-responder" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lpws5cv_a) {
  cx: 12px;
  cy: 6.5px;
  r: 3.75px;
}

:global(.oj484ac2v) {
  d: path("M4.25 21.25v-2a5.5 5.5 0 0 1 5.5-5.5h4.5a5.5 5.5 0 0 1 5.5 5.5v2ZM15.5 16v3M14 17.5h3");
}

</style>
