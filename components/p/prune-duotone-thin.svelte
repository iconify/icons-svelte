<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydrfk9w6p"/><path class="jpfwhpbab"/><path class="ww1qa5bbn"/><path class="i_15enoqb"/><path class="rb2jzlb5g"/><path class="mpjdm200q"/><path class="ngnirel9c"/><path class="hcq4p1b2v"/><path class="b1a3u6bfq"/><path class="ax4bccbjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prune-duotone-thin" {...props}></Icon>
<style>
:global(.ax4bccbjb) {
  d: path("m20 7 -4 4");
}

:global(.b1a3u6bfq) {
  d: path("m16 7 4 4");
}

:global(.hcq4p1b2v) {
  d: path("M6 15h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_15enoqb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jpfwhpbab) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mpjdm200q) {
  d: path("M6 4v16");
}

:global(.ngnirel9c) {
  d: path("M6 9h8");
}

:global(.rb2jzlb5g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ww1qa5bbn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ydrfk9w6p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
