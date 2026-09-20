<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oti3l4bvo"/><path class="ozi-k-boi"/><path class="hdk8dzk2v"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bunk-bed-outline-regular" {...props}></Icon>
<style>
:global(.hdk8dzk2v) {
  d: path("M3 21v-7h18v7");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oti3l4bvo) {
  d: path("M3 11V4h18v7");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

</style>
