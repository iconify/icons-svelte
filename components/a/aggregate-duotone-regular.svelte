<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ab0192bki"/><path class="s0wwcab9o"/><path class="e1t1m_b5m"/><path class="bxffck7nz"/><path class="goxee6bnt"/><path class="s9xdwbcyw"/><path class="pesxdybze"/><path class="nkayykbew"/><path class="b603-acaz"/><path class="adiugjbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aggregate-duotone-regular" {...props}></Icon>
<style>
:global(.ab0192bki) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 5 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.adiugjbhs) {
  d: path("m15 9 3 3 -3 3");
}

:global(.b603-acaz) {
  d: path("M10 12h8");
}

:global(.bxffck7nz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e1t1m_b5m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 19 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.goxee6bnt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nkayykbew) {
  d: path("m3 19 7 -7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pesxdybze) {
  d: path("M3 12h7");
}

:global(.s0wwcab9o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9xdwbcyw) {
  d: path("m3 5 7 7");
}

</style>
