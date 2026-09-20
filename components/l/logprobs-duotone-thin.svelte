<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="euj6eqbac"/><path class="moc63lp3w"/><path class="sv2vrddhu"/><path class="mg7aqnbsf"/><path class="it88l1wbh"/><path class="nbib5l08z"/><path class="cxyu2ib7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logprobs-duotone-thin" {...props}></Icon>
<style>
:global(.cxyu2ib7h) {
  d: path("M17 7v12");
}

:global(.euj6eqbac) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it88l1wbh) {
  d: path("M7 7v10");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.moc63lp3w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nbib5l08z) {
  d: path("M12 7v14");
}

:global(.r0_oskb4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sv2vrddhu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
