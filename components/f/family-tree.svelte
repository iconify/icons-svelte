<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="vyahqzb6p"/><circle class="v4m_bcc1n"/><circle class="rd52c4g0k"/><path class="ymp3_lbre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:family-tree" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rd52c4g0k) {
  cx: 18.5px;
  cy: 10.75px;
  r: 2.25px;
}

:global(.v4m_bcc1n) {
  cx: 5.5px;
  cy: 10.75px;
  r: 2.25px;
}

:global(.vyahqzb6p) {
  cx: 12px;
  cy: 6.5px;
  r: 2.5px;
}

:global(.ymp3_lbre) {
  d: path("M12 21.25V9m0 7.75l-5.25-4m5.25 4l5.25-4m-9 8.5h7.5");
}

</style>
