<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojgs7w76t"/><path class="f28ivhkon"/><path class="b1vuo5bge"/><path class="n68zqk-yy"/><path class="y5mud21bh"/><path class="otb2wbb6e"/><path class="wj4cfmbhq"/><path class="ms85c68gf"/><path class="i6ydbdc_n"/><path class="eud-3ptuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nat-duotone-thin" {...props}></Icon>
<style>
:global(.b1vuo5bge) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eud-3ptuk) {
  d: path("M15 12h7");
}

:global(.f28ivhkon) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6ydbdc_n) {
  d: path("m9 4 6 6v4l-6 6");
}

:global(.ms85c68gf) {
  d: path("M2 20h7");
}

:global(.n68zqk-yy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 4 6 6v4l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ojgs7w76t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.otb2wbb6e) {
  d: path("M2 4h7");
}

:global(.wj4cfmbhq) {
  d: path("M2 12h7");
}

:global(.y5mud21bh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
