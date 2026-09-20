<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pbd66000m"/><path class="s2gl1vbxy"/><path class="f5touvbja"/><path class="hlxudebgl"/><path class="o46_3ibvz"/><path class="gzh4n16ws"/><path class="b6ubinbne"/><path class="ti0atfbnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:robot-arm-duotone-bold" {...props}></Icon>
<style>
:global(.b6ubinbne) {
  d: path("m6 12 6 -6h8v3.5");
}

:global(.f5touvbja) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 12 6 -6h8v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gzh4n16ws) {
  d: path("M6 12v8");
}

:global(.hlxudebgl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 6v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o46_3ibvz) {
  d: path("M3 20h6");
}

:global(.pbd66000m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s2gl1vbxy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ti0atfbnf) {
  d: path("M17 6v3.5");
}

</style>
