<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jqvj67jvf"/><path class="qgw5bw59f"/><path class="o2mxw0jtm"/><path class="i9lkiobzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guitar-outline-bold" {...props}></Icon>
<style>
:global(.i9lkiobzn) {
  d: path("M10 5V2h4v3Z");
}

:global(.jqvj67jvf) {
  d: path("M12 21c-3.5 0 -6 -2 -6 -4.5 0 -3 2.5 -4 3 -5.5h6c0.5 1.5 3 2.5 3 5.5 0 2.5 -2.5 4.5 -6 4.5");
}

:global(.o2mxw0jtm) {
  d: path("M12 5v6");
}

:global(.qgw5bw59f) {
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
