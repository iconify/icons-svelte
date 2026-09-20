<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yigkywbyn"/><path class="ry5l7ebuo"/><path class="ot37jibbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:marker-pen-outline-bold" {...props}></Icon>
<style>
:global(.ot37jibbb) {
  d: path("m10 16 4 -4");
}

:global(.ry5l7ebuo) {
  d: path("m5 17 3 -3 4 4 -3 3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yigkywbyn) {
  d: path("m8 14 8 -8 4 4 -8 8Z");
}

</style>
