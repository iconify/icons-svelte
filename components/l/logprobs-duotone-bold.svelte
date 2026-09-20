<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="u2tke5gjo"/><path class="mjd3bubhw"/><path class="d-27ccc0v"/><path class="mg7aqnbsf"/><path class="it88l1wbh"/><path class="nbib5l08z"/><path class="cxyu2ib7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logprobs-duotone-bold" {...props}></Icon>
<style>
:global(.aqn8oeb4o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cxyu2ib7h) {
  d: path("M17 7v12");
}

:global(.d-27ccc0v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.it88l1wbh) {
  d: path("M7 7v10");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.mjd3bubhw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nbib5l08z) {
  d: path("M12 7v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u2tke5gjo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
