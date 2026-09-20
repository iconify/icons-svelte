<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ni20md-jo"/><path class="j6o0shbiv"/><path class="uesvxd39h"/><path class="bt8rz4blr"/><path class="zii0blbzf"/><path class="gszndw_am"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-batch-outline-bold" {...props}></Icon>
<style>
:global(.bt8rz4blr) {
  d: path("M9.5 6H7v8h2.5");
}

:global(.gszndw_am) {
  d: path("M10 11.5h6");
}

:global(.j6o0shbiv) {
  d: path("M7 18h5");
}

:global(.ni20md-jo) {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uesvxd39h) {
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zii0blbzf) {
  d: path("M10 8.5h6");
}

</style>
