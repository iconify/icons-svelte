<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q31y1lb9i"/><path class="ci4oydb4u"/><path class="w69svbcwu"/><path class="am7eiccgy"/><path class="r4nj1cczx"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:groupby-duotone-thin" {...props}></Icon>
<style>
:global(.am7eiccgy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ci4oydb4u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eu9kkgbdm) {
  d: path("M9 12h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q31y1lb9i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4H3v16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r4nj1cczx) {
  d: path("M6 4H3v16h3");
}

:global(.sxy07wbdf) {
  d: path("M9 7h12");
}

:global(.w69svbcwu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x3jqftbaj) {
  d: path("M9 17h12");
}

</style>
