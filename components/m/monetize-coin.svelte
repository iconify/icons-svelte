<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jg7xt1_6k"/><path class="qkyty1fbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monetize-coin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jg7xt1_6k) {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
}

:global(.qkyty1fbh) {
  d: path("M12 11.75c-.35-.65-1.05-1-2-1c-1.2 0-2 .6-2 1.5c0 2 4 1 4 3c0 .9-.8 1.5-2 1.5c-.95 0-1.65-.35-2-1m2-6v1m0 6.5v1m5.75-15.5h5.5v5.5m0-5.5l-5 5");
}

</style>
