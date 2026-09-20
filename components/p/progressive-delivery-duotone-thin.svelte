<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="c_5qv0bez"/><path class="frsnihqwo"/><path class="y00djcbfo"/><path class="ri2m-q_tv"/><path class="r3uulhbhd"/><path class="n-fiqpbfy"/><path class="kw1bmjbqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:progressive-delivery-duotone-thin" {...props}></Icon>
<style>
:global(.c_5qv0bez) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.frsnihqwo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

:global(.vws5wpblq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y00djcbfo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
