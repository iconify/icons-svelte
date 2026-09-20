<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ykm0cs8hk"/><path class="ntt8cbcqj"/><path class="l77-u97tm"/><path class="vxhsoobap"/><path class="kv86m5bsi"/><path class="pfpu_3ppl"/><path class="dm5ccobgo"/><path class="mcj52c2nx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:history-duotone-thin" {...props}></Icon>
<style>
:global(.dm5ccobgo) {
  d: path("M12 12h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kv86m5bsi) {
  d: path("M3 4v5h5");
}

:global(.l77-u97tm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcj52c2nx) {
  d: path("M12 3a9 9 0 1 1 -9 9");
}

:global(.ntt8cbcqj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.vxhsoobap) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3a9 9 0 1 1 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ykm0cs8hk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4v5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
