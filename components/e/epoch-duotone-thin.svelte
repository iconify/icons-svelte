<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxhsoobap"/><path class="gpdpgob7k"/><path class="ivq-6sb9r"/><path class="mcj52c2nx"/><path class="hwkcvpp-j"/><path class="ihfql7bsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:epoch-duotone-thin" {...props}></Icon>
<style>
:global(.gpdpgob7k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6a6 6 0 1 1 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwkcvpp-j) {
  d: path("M12 6a6 6 0 1 1 -6 6");
}

:global(.ihfql7bsw) {
  d: path("M12 9a3 3 0 1 1 -3 3");
}

:global(.ivq-6sb9r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcj52c2nx) {
  d: path("M12 3a9 9 0 1 1 -9 9");
}

:global(.vxhsoobap) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3a9 9 0 1 1 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
