<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk3-upbdr"/><path class="exchjjbzd"/><path class="ok6fpacim"/><path class="s994z3b0d"/><path class="ubojtpbkq"/><path class="vhf3_kexp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pin-duotone-thin" {...props}></Icon>
<style>
:global(.exchjjbzd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 5v8l3 3 3 -3V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ok6fpacim) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s994z3b0d) {
  d: path("M6 5h12");
}

:global(.sk3-upbdr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ubojtpbkq) {
  d: path("M9 5v8l3 3 3 -3V5");
}

:global(.vhf3_kexp) {
  d: path("M12 16v5");
}

</style>
