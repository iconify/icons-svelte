<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r1gclvbbm"/><path class="ks2swpbkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:done-all-outline-bold" {...props}></Icon>
<style>
:global(.ks2swpbkw) {
  d: path("m9 12 5 5 8 -8");
}

:global(.r1gclvbbm) {
  d: path("m2 12 5 5 8 -8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
