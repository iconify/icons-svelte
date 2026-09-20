<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zfjwcz4-w"/><path class="k3m1vd7mo"/><path class="m53fnk4nh"/><path class="i4csqewjm"/><path class="cojy4nbyv"/><path class="vhfgw5-us"/><path class="a-ogebbgz"/><path class="e2evtpg8i"/><path class="q4rhaacat"/><path class="hv2_9fjhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detour-duotone-regular" {...props}></Icon>
<style>
:global(.a-ogebbgz) {
  d: path("M12 7v9");
}

:global(.cojy4nbyv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 13 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e2evtpg8i) {
  d: path("M9.5 9.5 12 7l2.5 2.5");
}

:global(.hv2_9fjhy) {
  d: path("m20 13 -4 4");
}

:global(.i4csqewjm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 13 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k3m1vd7mo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m53fnk4nh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 9.5 12 7l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q4rhaacat) {
  d: path("m16 13 4 4");
}

:global(.vhfgw5-us) {
  d: path("M2 16h10");
}

:global(.zfjwcz4-w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
