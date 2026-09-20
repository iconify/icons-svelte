<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="att80_4qt"/><path class="n992mnnno"/><path class="srdvrnblq"/><path class="s994z3b0d"/><path class="ubojtpbkq"/><path class="vhf3_kexp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pin-duotone-regular" {...props}></Icon>
<style>
:global(.att80_4qt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n992mnnno) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 5v8l3 3 3 -3V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s994z3b0d) {
  d: path("M6 5h12");
}

:global(.srdvrnblq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ubojtpbkq) {
  d: path("M9 5v8l3 3 3 -3V5");
}

:global(.vhf3_kexp) {
  d: path("M12 16v5");
}

</style>
