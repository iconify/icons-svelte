<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pus9z-bwo"/><path class="pfpu_3ppl"/><path class="k2i6ze2yw"/><path class="y7kkpcbjj"/><path class="oqx2fjbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-family-outline-bold" {...props}></Icon>
<style>
:global(.k2i6ze2yw) {
  d: path("M6 15v-3h12v3");
}

:global(.oqx2fjbwx) {
  d: path("m18 15 3 3 -3 3 -3 -3Z");
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.pus9z-bwo) {
  d: path("m12 2 3 3 -3 3 -3 -3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y7kkpcbjj) {
  d: path("m6 15 3 3 -3 3 -3 -3Z");
}

</style>
