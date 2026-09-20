<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGLvCMfelJ"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="kvddbzdha"/><path class="wgfmlvbwg"/><path class="oml4dqbmk"/></g></mask></defs><circle mask="url(#SVGLvCMfelJ)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-down-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.kvddbzdha) {
  d: path("M17.768 14.027a1 1 0 0 1-.128 1.408l-4 3.333a1 1 0 0 1-1.28-1.536l4-3.334a1 1 0 0 1 1.408.129");
}

:global(.kvn14gsjy) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

:global(.oml4dqbmk) {
  d: path("M13 17a1 1 0 0 1-1-1V8a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

:global(.wgfmlvbwg) {
  d: path("M8.232 14.027a1 1 0 0 1 1.408-.129l4 3.334a1 1 0 1 1-1.28 1.536l-4-3.333a1 1 0 0 1-.128-1.408");
}

</style>
