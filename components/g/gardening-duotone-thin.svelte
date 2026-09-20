<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwbt03y-u"/><path class="lio8itbog"/><path class="e0khk-b9n"/><path class="pwxki4zra"/><path class="ngex86bxe"/><path class="hsnj9o-9y"/><path class="kf-dg5j1v"/><path class="s09hy0b0y"/><path class="rx24zrjxq"/><path class="acx2mjbnt"/><path class="ftrg70bds"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gardening-duotone-thin" {...props}></Icon>
<style>
:global(.acx2mjbnt) {
  d: path("M12 11v6");
}

:global(.e0khk-b9n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftrg70bds) {
  d: path("M17 11v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.kf-dg5j1v) {
  d: path("M12 2v9");
}

:global(.kwbt03y-u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lio8itbog) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ngex86bxe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pwxki4zra) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rx24zrjxq) {
  d: path("M7 11v6");
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

</style>
