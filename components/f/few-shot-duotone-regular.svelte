<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l31lw8bqy"/><path class="bj5ndtr6c"/><path class="dynn30blv"/><path class="ziq0wmbxt"/><path class="bgjpknbib"/><path class="q95wyyyjq"/><path class="t407ddc6o"/><path class="dcemxxfpc"/><path class="uv_v7wb2g"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:few-shot-duotone-regular" {...props}></Icon>
<style>
:global(.bgjpknbib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bj5ndtr6c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dcemxxfpc) {
  d: path("M3 19h8");
}

:global(.dynn30blv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l31lw8bqy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q95wyyyjq) {
  d: path("M3 5h8");
}

:global(.t407ddc6o) {
  d: path("M3 12h8");
}

:global(.uv_v7wb2g) {
  d: path("M14 12h5");
}

:global(.ziq0wmbxt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

</style>
