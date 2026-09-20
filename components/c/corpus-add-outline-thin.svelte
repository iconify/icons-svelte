<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5d2grbwo"/><path class="s27ukbqxc"/><path class="jls6b8fnh"/><path class="l9kfpmzgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corpus-add-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i5d2grbwo) {
  d: path("M13 2H6v14h10V5");
}

:global(.jls6b8fnh) {
  d: path("M16.5 4.5h5");
}

:global(.l9kfpmzgx) {
  d: path("M19 2v5");
}

:global(.s27ukbqxc) {
  d: path("M16 8H9v14h10V11");
}

</style>
