<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="it88l1wbh"/><path class="nbib5l08z"/><path class="cxyu2ib7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logprobs-outline-regular" {...props}></Icon>
<style>
:global(.cxyu2ib7h) {
  d: path("M17 7v12");
}

:global(.it88l1wbh) {
  d: path("M7 7v10");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.nbib5l08z) {
  d: path("M12 7v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
