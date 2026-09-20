<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="n7jtegbzu"/><path class="xf6rxlb8o"/><path class="fc8gspe8z"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="gjllsvbkd"/><path class="g-zzhsbrv"/><path class="r_4k1sbsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multi-query-duotone-bold" {...props}></Icon>
<style>
:global(.fc8gspe8z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.g-zzhsbrv) {
  d: path("M7 10h6");
}

:global(.gjllsvbkd) {
  d: path("M7 7h6");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.n7jtegbzu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.plw-owhdh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r_4k1sbsg) {
  d: path("M7 13h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xf6rxlb8o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yjc9h6oua) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
