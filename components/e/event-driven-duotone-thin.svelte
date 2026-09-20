<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v52nc_bbx"/><path class="t-3s33n5f"/><path class="b8su7584a"/><path class="d251mrbie"/><path class="ukjt4fb6s"/><path class="o035hszqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-driven-duotone-thin" {...props}></Icon>
<style>
:global(.b8su7584a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 14 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d251mrbie) {
  d: path("m16 3 -5 5h3l-5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o035hszqc) {
  d: path("m14 14 3 3 -3 3");
}

:global(.t-3s33n5f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ukjt4fb6s) {
  d: path("M3 17h12");
}

:global(.v52nc_bbx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 3 -5 5h3l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
