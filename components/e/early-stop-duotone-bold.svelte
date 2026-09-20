<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i7nok491l"/><path class="fgef0hcge"/><path class="gh1l41bbm"/><path class="t3rq50btb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:early-stop-duotone-bold" {...props}></Icon>
<style>
:global(.fgef0hcge) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gh1l41bbm) {
  d: path("m3 5 6 6h4l3 3");
}

:global(.i7nok491l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 5 6 6h4l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

</style>
