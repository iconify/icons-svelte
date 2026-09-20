<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="cb-v5c5ba"/><path class="p5hd8ygud"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="strt8mboj"/><path class="p8yct170k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keyword-search-duotone-bold" {...props}></Icon>
<style>
:global(.cb-v5c5ba) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.p5hd8ygud) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8yct170k) {
  d: path("M7 12h6");
}

:global(.plw-owhdh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.strt8mboj) {
  d: path("M7 8h6");
}

:global(.yjc9h6oua) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
