<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bn_pu6j-z"/><path class="ioj0a6btg"/><path class="oav48zkig"/><path class="woh6qyb5h"/><path class="cd54abpwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:folder-sync-outline-bold" {...props}></Icon>
<style>
:global(.bn_pu6j-z) {
  d: path("M20 7v13H4V4h5l3 3h4");
}

:global(.cd54abpwo) {
  d: path("m11.5 13 -2 2 2 2");
}

:global(.ioj0a6btg) {
  d: path("M9 11.5h5.5");
}

:global(.oav48zkig) {
  d: path("m12.5 9.5 2 2 -2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.woh6qyb5h) {
  d: path("M9.5 15H15");
}

</style>
