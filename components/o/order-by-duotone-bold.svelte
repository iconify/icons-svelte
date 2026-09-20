<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="kfua5lbaj"/><path class="j-myddb5e"/><path class="pbd66000m"/><path class="k6nj2fbya"/><path class="qxnpdo0dk"/><path class="zuu1wnb1v"/><path class="o46_3ibvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:order-by-duotone-bold" {...props}></Icon>
<style>
:global(.h7vr07ufd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j-myddb5e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.kfua5lbaj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h14");
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

:global(.qxnpdo0dk) {
  d: path("M3 10h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zuu1wnb1v) {
  d: path("M3 15h10");
}

</style>
