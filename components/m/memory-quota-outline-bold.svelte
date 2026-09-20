<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n0n63pb2v"/><path class="ylrudh6bl"/><path class="l2oprob0y"/><path class="qr1iqpomq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-quota-outline-bold" {...props}></Icon>
<style>
:global(.l2oprob0y) {
  d: path("M17 5v6");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.qr1iqpomq) {
  d: path("M9 8h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ylrudh6bl) {
  d: path("M7 5v6");
}

</style>
