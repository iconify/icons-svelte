<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="bpe5ncr9i"/><path class="zc6ogu6ot"/><path class="yy6zh0q6d"/><path class="mg7aqnbsf"/><path class="it88l1wbh"/><path class="nbib5l08z"/><path class="cxyu2ib7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logprobs-duotone-regular" {...props}></Icon>
<style>
:global(.bpe5ncr9i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

:global(.s1ajs51ib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yy6zh0q6d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zc6ogu6ot) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
