<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="elj7lmb0r"/><path class="iwlcqzzwf"/><circle class="aemasgwuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nursing-mother" {...props}></Icon>
<style>
:global(.aemasgwuc) {
  cx: 14px;
  cy: 11.5px;
  r: 2px;
}

:global(.elj7lmb0r) {
  cx: 9.5px;
  cy: 5.5px;
  r: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwlcqzzwf) {
  d: path("M5 21v-6a3.5 3.5 0 0 1 3.5-3.5H9a5 5 0 0 0 10 0");
}

</style>
