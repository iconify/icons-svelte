<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t-6vihbqs"/><path class="esplf8bcv"/><path class="gl5tnbc1a"/><path class="nz19jcivh"/><path class="ov7kkt0lo"/><path class="vxy4ztabh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:earthquake-duotone-thin" {...props}></Icon>
<style>
:global(.esplf8bcv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 17 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gl5tnbc1a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nz19jcivh) {
  d: path("M2 10h4l3 -3 3 3 3 -3 3 3h4");
}

:global(.ov7kkt0lo) {
  d: path("m8 17 4 4 4 -4");
}

:global(.t-6vihbqs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 10h4l3 -3 3 3 3 -3 3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vxy4ztabh) {
  d: path("M4 14h16");
}

</style>
