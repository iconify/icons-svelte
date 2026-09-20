<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_qnepbtm"/><path class="e1s2le8fv"/><path class="lmc6jyb6f"/><path class="p41-m0bke"/><path class="vg0qlegui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-tree-outline-bold" {...props}></Icon>
<style>
:global(.e1s2le8fv) {
  d: path("M5 10h6");
}

:global(.lmc6jyb6f) {
  d: path("M14 10h7");
}

:global(.p41-m0bke) {
  d: path("M5 17h6");
}

:global(.s_qnepbtm) {
  d: path("M5 3v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vg0qlegui) {
  d: path("M14 17h7");
}

</style>
