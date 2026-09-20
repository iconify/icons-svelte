<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="au0irbcan"/><path class="nb4sj2weg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:angle-left" {...props}></Icon>
<style>
:global(.au0irbcan) {
  d: path("M6.732 10.64a1 1 0 1 1 1.536-1.28l5 6a1 1 0 1 1-1.536 1.28z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nb4sj2weg) {
  d: path("M8.268 10.64a1 1 0 1 1-1.536-1.28l5-6a1 1 0 1 1 1.536 1.28z");
}

</style>
