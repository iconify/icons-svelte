<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="f979qth3u"/><path class="i9z26v4id"/><path class="d50iifbha"/><path class="nyant1n6t"/><path class="jmsqj3nfg"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:contract-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d50iifbha) {
  d: path("M12 9a1 1 0 1 1-2 0V5a1 1 0 1 1 2 0zm-6.293 6.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

:global(.f979qth3u) {
  d: path("M11.707 9.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

:global(.i9z26v4id) {
  d: path("M11 10a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

:global(.jmsqj3nfg) {
  d: path("M5 12a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

:global(.nyant1n6t) {
  d: path("M10 15a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0z");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
