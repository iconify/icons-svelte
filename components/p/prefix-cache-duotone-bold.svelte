<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x87wa6b5t"/><path class="lx3jyybfn"/><path class="faaxtxspp"/><path class="l80popahq"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="jlfjgzbqx"/><path class="kvfieo68l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prefix-cache-duotone-bold" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.faaxtxspp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.kvfieo68l) {
  d: path("M13.5 11 11 13.5h2.5L11 16");
}

:global(.l80popahq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 11 11 13.5h2.5L11 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lx3jyybfn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x87wa6b5t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
