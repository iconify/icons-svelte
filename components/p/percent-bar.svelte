<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wc6025c8w"/><rect class="l2e-pnbhq"/><rect class="rl3gbz0ih"/><rect class="wxla0klvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:percent-bar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l2e-pnbhq) {
  width: 5px;
  height: 5px;
  x: 16.25px;
  y: 4.75px;
  rx: 1.5px;
}

:global(.rl3gbz0ih) {
  width: 6.5px;
  height: 5px;
  x: 2.75px;
  y: 14.25px;
  rx: 1.5px;
}

:global(.wc6025c8w) {
  width: 11px;
  height: 5px;
  x: 2.75px;
  y: 4.75px;
  rx: 1.5px;
}

:global(.wxla0klvc) {
  width: 9.5px;
  height: 5px;
  x: 11.75px;
  y: 14.25px;
  rx: 1.5px;
}

</style>
