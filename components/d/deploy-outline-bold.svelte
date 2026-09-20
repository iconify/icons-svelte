<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zt9xgrbcr"/><path class="uvgrx_yvv"/><path class="tdul-wdwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deploy-outline-bold" {...props}></Icon>
<style>
:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tdul-wdwn) {
  d: path("m9 6 3 -3 3 3");
}

:global(.uvgrx_yvv) {
  d: path("M12 3v5");
}

:global(.zt9xgrbcr) {
  d: path("M13.5 11H17a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-3a3 3 0 0 1 3 -3h3.5");
}

</style>
