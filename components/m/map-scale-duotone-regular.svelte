<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="digwvcbca"/><path class="l9q4-o2vn"/><path class="qyu-vobur"/><path class="za--46bps"/><path class="o_dpikbpd"/><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-scale-duotone-regular" {...props}></Icon>
<style>
:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.digwvcbca) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.h_c4fk0bb) {
  d: path("M3 11v6");
}

:global(.l3hfq7bhw) {
  d: path("M9 11v4");
}

:global(.l9q4-o2vn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lfyekl_xx) {
  d: path("M21 11v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o_dpikbpd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qyu-vobur) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.za--46bps) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
