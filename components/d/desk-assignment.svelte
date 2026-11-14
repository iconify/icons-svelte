<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uazw20bli"/><path class="w_8484bmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:desk-assignment" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uazw20bli) {
  d: path("M2.5 15h19m-17 0v6m15-6v6M12 15s-4.75-4-4.75-7.25a4.75 4.75 0 0 1 9.5 0C16.75 11 12 15 12 15");
}

:global(.w_8484bmm) {
  d: path("M10.5 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
