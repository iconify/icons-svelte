<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oepw4czzw"/><path class="lbllh8b8w"/><path class="r52nu-zqu"/><path class="wfd9yacqd"/><path class="oti3l4bvo"/><path class="ozi-k-boi"/><path class="hdk8dzk2v"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bunk-bed-duotone-regular" {...props}></Icon>
<style>
:global(.hdk8dzk2v) {
  d: path("M3 21v-7h18v7");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.lbllh8b8w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oepw4czzw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11V4h18v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oti3l4bvo) {
  d: path("M3 11V4h18v7");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.r52nu-zqu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21v-7h18v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wfd9yacqd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
