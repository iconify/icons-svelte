<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdwo9hb6a"/><path class="wv6md6qod"/><path class="h003j4fqe"/><path class="ksrg26b8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bookmark-off-duotone-thin" {...props}></Icon>
<style>
:global(.h003j4fqe) {
  d: path("m10 8 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ksrg26b8a) {
  d: path("m14 8 -4 4");
}

:global(.wv6md6qod) {
  d: path("M15 3h3v18l-6 -6 -6 6V3h3");
}

:global(.xdwo9hb6a) {
  fill: currentColor;
  d: path("M15 3h3v18l-6 -6 -6 6V3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
