<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s7h04rdua"/><path class="qxwxnhbhy"/><path class="olma08bid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:eval-rag-outline-bold" {...props}></Icon>
<style>
:global(.olma08bid) {
  d: path("m13 17 2.5 2.5L20 15");
}

:global(.qxwxnhbhy) {
  d: path("M12.5 12.5 16 16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s7h04rdua) {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

</style>
