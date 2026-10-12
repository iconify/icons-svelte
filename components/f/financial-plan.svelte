<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="tibu_bctd"/><circle class="pprsu-mfw"/><path class="inu9xmyyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:financial-plan" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.inu9xmyyz) {
  d: path("M12.13 12.02c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73M14 10l4.75-4.75m0-2.5v2.5h2.5");
}

:global(.pprsu-mfw) {
  cx: 11px;
  cy: 13px;
  r: 4.25px;
}

:global(.tibu_bctd) {
  cx: 11px;
  cy: 13px;
  r: 8.25px;
}

</style>
