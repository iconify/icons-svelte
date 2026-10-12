<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpufevaxf"/><circle class="m_ubk9bxa"/><circle class="m_gjb-bcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mobility-scooter" {...props}></Icon>
<style>
:global(.fpufevaxf) {
  d: path("M17 4v9.25H6M14.5 4H17M6 6v3h4M8 9v4.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_gjb-bcb) {
  cx: 16px;
  cy: 18.75px;
  r: 2.5px;
}

:global(.m_ubk9bxa) {
  cx: 7px;
  cy: 18.75px;
  r: 2.5px;
}

</style>
