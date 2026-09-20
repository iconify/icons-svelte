<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nm1tlbreh"/><path class="e03jjq99j"/><path class="emvotkb4z"/><path class="m26ojxb3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-diff-outline-bold" {...props}></Icon>
<style>
:global(.e03jjq99j) {
  d: path("M4 7h6");
}

:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.m26ojxb3w) {
  d: path("M14 17h6");
}

:global(.nm1tlbreh) {
  d: path("M7 4v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
