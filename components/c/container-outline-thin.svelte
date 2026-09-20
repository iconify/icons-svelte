<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxsav7b5u"/><path class="vavi9cbgb"/><path class="x5li7lwaz"/><path class="bppr_wbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:container-outline-thin" {...props}></Icon>
<style>
:global(.bppr_wbcq) {
  d: path("M16 7v12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vavi9cbgb) {
  d: path("M8 7v12");
}

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

:global(.xxsav7b5u) {
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
