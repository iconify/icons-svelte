<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lcyinnbmm"/><circle class="u_qlszbyq"/><circle class="idf1-xb5a"/><circle class="m8k5k22cc"/><circle class="mscsd_b2w"/><circle class="zopjch_2q"/><path class="rsjxg36qn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:grapes" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.idf1-xb5a) {
  cx: 18.5px;
  cy: 7.5px;
  r: 2px;
}

:global(.lcyinnbmm) {
  cx: 5.5px;
  cy: 7.5px;
  r: 2px;
}

:global(.m8k5k22cc) {
  cx: 8.75px;
  cy: 13.25px;
  r: 2px;
}

:global(.mscsd_b2w) {
  cx: 15.25px;
  cy: 13.25px;
  r: 2px;
}

:global(.rsjxg36qn) {
  d: path("M12 5.5c0-1.5.75-2.75 2.5-2.75");
}

:global(.u_qlszbyq) {
  cx: 12px;
  cy: 7.5px;
  r: 2px;
}

:global(.zopjch_2q) {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>
