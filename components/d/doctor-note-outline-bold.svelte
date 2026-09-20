<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4_6s7b5v"/><path class="o2mxw0jtm"/><path class="qr1iqpomq"/><path class="j4po9lbmx"/><path class="g_cfe6uls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:doctor-note-outline-bold" {...props}></Icon>
<style>
:global(.g_cfe6uls) {
  d: path("m10 16 3 -3 4 4");
}

:global(.j4po9lbmx) {
  d: path("M7 16h3");
}

:global(.o2mxw0jtm) {
  d: path("M12 5v6");
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

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
