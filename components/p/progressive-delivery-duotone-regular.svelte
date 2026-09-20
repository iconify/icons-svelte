<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="rneodbv1f"/><path class="jcigmbc2x"/><path class="jkb4mywmt"/><path class="ri2m-q_tv"/><path class="r3uulhbhd"/><path class="n-fiqpbfy"/><path class="kw1bmjbqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:progressive-delivery-duotone-regular" {...props}></Icon>
<style>
:global(.jcigmbc2x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkb4mywmt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kw1bmjbqj) {
  d: path("M16 8v7");
}

:global(.n-fiqpbfy) {
  d: path("M12 10v5");
}

:global(.n5v54kp1e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r3uulhbhd) {
  d: path("M8 12v3");
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.rneodbv1f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
