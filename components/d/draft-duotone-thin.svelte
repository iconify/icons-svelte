<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etuphyhyp"/><path class="o0lh1k1dl"/><path class="z1t2-_6ze"/><path class="w0as59itk"/><path class="jlfjgzbqx"/><path class="aum97lbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:draft-duotone-thin" {...props}></Icon>
<style>
:global(.aum97lbyp) {
  d: path("M9 13h4");
}

:global(.etuphyhyp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 3H6v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.o0lh1k1dl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w0as59itk) {
  d: path("M13 3H6v18h8");
}

:global(.z1t2-_6ze) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 13h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
