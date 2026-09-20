<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x2vm1eh6r"/><path class="va9i39bae"/><path class="j4a3yvbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blood-test-outline-bold" {...props}></Icon>
<style>
:global(.j4a3yvbid) {
  d: path("m12 9 3 3a4 4 0 0 1 -6 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.va9i39bae) {
  d: path("M7 3h10");
}

:global(.x2vm1eh6r) {
  d: path("M9 3v15h6V3");
}

</style>
