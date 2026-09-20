<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gtlfk7rgu"/><path class="b5ic9acln"/><path class="w4qqntb0t"/><path class="gw7hjrxbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bi-encoder-duotone-regular" {...props}></Icon>
<style>
:global(.b5ic9acln) {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

:global(.gtlfk7rgu) {
  fill: currentColor;
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gw7hjrxbz) {
  d: path("M14.5 10.5v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w4qqntb0t) {
  d: path("M9.5 10.5v5");
}

</style>
