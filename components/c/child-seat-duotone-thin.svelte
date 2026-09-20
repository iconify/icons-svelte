<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gju2vx3wu"/><path class="mwny3bbtr"/><path class="dhw73cmjs"/><path class="phi1ncbih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:child-seat-duotone-thin" {...props}></Icon>
<style>
:global(.dhw73cmjs) {
  d: path("M6 21V6l3 -3h7v12h3v6");
}

:global(.gju2vx3wu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21V6l3 -3h7v12h3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mwny3bbtr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.phi1ncbih) {
  d: path("M6 15h10");
}

</style>
