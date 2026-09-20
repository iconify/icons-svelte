<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kk4vcs1ji"/><path class="gumem2bkh"/><path class="ov7kkt0lo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-layer-outline-regular" {...props}></Icon>
<style>
:global(.gumem2bkh) {
  d: path("m6 13 6 6 6 -6");
}

:global(.kk4vcs1ji) {
  d: path("m12 2 7 7 -7 7 -7 -7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ov7kkt0lo) {
  d: path("m8 17 4 4 4 -4");
}

</style>
