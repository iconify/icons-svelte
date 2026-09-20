<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hp4yyybmk"/><path class="k7-ui8bdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-line-down-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hp4yyybmk) {
  d: path("m208 72l-80 80l-80-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k7-ui8bdn) {
  d: path("M122.34 157.66a8 8 0 0 0 11.32 0l80-80A8 8 0 0 0 208 64H48a8 8 0 0 0-5.66 13.66ZM188.69 80L128 140.69L67.31 80ZM216 192a8 8 0 0 1-8 8H48a8 8 0 0 1 0-16h160a8 8 0 0 1 8 8");
}

</style>
