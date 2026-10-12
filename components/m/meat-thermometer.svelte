<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ix1rbnbtt"/><path class="jy2bq-bpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:meat-thermometer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ix1rbnbtt) {
  cx: 12px;
  cy: 8px;
  r: 5.25px;
}

:global(.jy2bq-bpt) {
  d: path("M12 8L9.4 6.5m2.6 6.75v8");
}

</style>
