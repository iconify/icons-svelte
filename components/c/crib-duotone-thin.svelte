<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9jzbjbwv"/><path class="hsnj9o-9y"/><path class="rcvpd8b-f"/><path class="n8sts3-0i"/><path class="rvgi8v2qv"/><path class="yf6o7bb_j"/><path class="vhnbtvbtn"/><path class="jkuojibnm"/><path class="h7wibbbny"/><path class="ler50rfbf"/><path class="xl6k1lbjd"/><path class="y4qjbbcmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crib-duotone-thin" {...props}></Icon>
<style>
:global(.h7wibbbny) {
  d: path("M3 6v14");
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

:global(.ler50rfbf) {
  d: path("M9 8v12");
}

:global(.n8sts3-0i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rcvpd8b-f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rvgi8v2qv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9jzbjbwv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.xl6k1lbjd) {
  d: path("M15 8v12");
}

:global(.y4qjbbcmm) {
  d: path("M21 6v14");
}

:global(.yf6o7bb_j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
