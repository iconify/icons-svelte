<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t7jqbzdsw"/><path class="eaep8gb-r"/><path class="nex0q68jd"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="uxyzhxvwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pii-mask-duotone-bold" {...props}></Icon>
<style>
:global(.eaep8gb-r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.moha5wbmp) {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

:global(.nex0q68jd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t7jqbzdsw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
