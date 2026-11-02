<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zpmn5wbqo"/><path class="ix9nbjbaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:coach-front-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ix9nbjbaz) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18V7a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v11zm2 0h2v2H6Zm10 0h2v2h-2ZM4 12h16M8 15h.01M16 15h.01");
}

:global(.zpmn5wbqo) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
