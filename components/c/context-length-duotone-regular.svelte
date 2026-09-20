<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bpqmg-bcl"/><path class="lgt3bbkcq"/><path class="im38brk4q"/><path class="ab69i60qd"/><path class="qebvfnl4i"/><path class="uxyzhxvwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-length-duotone-regular" {...props}></Icon>
<style>
:global(.ab69i60qd) {
  d: path("M5.5 4H3v16h2.5");
}

:global(.bpqmg-bcl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.im38brk4q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgt3bbkcq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 4H21v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qebvfnl4i) {
  d: path("M18.5 4H21v16h-2.5");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

</style>
