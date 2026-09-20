<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="km9uii_ku"/><path class="acn1wacgd"/><path class="j70g_4bdf"/><path class="bmf8oqbve"/><path class="ri2m-q_tv"/><path class="r3uulhbhd"/><path class="n-fiqpbfy"/><path class="kw1bmjbqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:progressive-delivery-duotone-bold" {...props}></Icon>
<style>
:global(.acn1wacgd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bmf8oqbve) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j70g_4bdf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km9uii_ku) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kw1bmjbqj) {
  d: path("M16 8v7");
}

:global(.n-fiqpbfy) {
  d: path("M12 10v5");
}

:global(.r3uulhbhd) {
  d: path("M8 12v3");
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
