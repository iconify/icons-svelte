<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w58qq-byw"/><path class="zrasp8b3z"/><path class="m8syjybid"/><path class="zqenluyrw"/><path class="kpl1hdb6r"/><path class="lbirm1b-l"/><path class="qv6cnabrq"/><path class="oqj-o0b2r"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="zpusjcvvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rake-duotone-thin" {...props}></Icon>
<style>
:global(.drjad9bfe) {
  d: path("M14 14v4");
}

:global(.evsu0jbbm) {
  d: path("M10 14v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kpl1hdb6r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ktxjg3b2q) {
  d: path("M6 14v4");
}

:global(.lbirm1b-l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m8syjybid) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.qv6cnabrq) {
  d: path("M12 3v11");
}

:global(.w58qq-byw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpusjcvvn) {
  d: path("M18 14v4");
}

:global(.zqenluyrw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zrasp8b3z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
