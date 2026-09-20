<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lrkxnckco"/><path class="aoorvnbzq"/><path class="e-eh9i0mi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-review-outline-bold" {...props}></Icon>
<style>
:global(.aoorvnbzq) {
  d: path("m14 7 4 4 -4 4");
}

:global(.e-eh9i0mi) {
  d: path("m9 19 2 2 4 -4");
}

:global(.lrkxnckco) {
  d: path("m8 7 -4 4 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
