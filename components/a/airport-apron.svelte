<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="et_rxcq_l"/><path class="bp74s_bbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:airport-apron" {...props}></Icon>
<style>
:global(.bp74s_bbx) {
  d: path("m5.5 13.5l6.5-4l6.5 4m-9.5 5l3-2l3 2");
}

:global(.et_rxcq_l) {
  d: path("M2.5 21.5v-17a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v17M12 5.5v13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
