<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r2pr1db3q"/><path clip-rule="evenodd" class="s4h7atb2u"/><path clip-rule="evenodd" class="sjskqhb8s"/><path clip-rule="evenodd" class="gv8kota8a"/><path clip-rule="evenodd" class="d-xs7hjej"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:down-up-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d-xs7hjej) {
  fill-rule: evenodd;
  d: path("M6 15a1 1 0 0 1-1-1V6a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

:global(.gv8kota8a) {
  fill-rule: evenodd;
  d: path("M2.293 12.293a1 1 0 0 1 1.414 0l3 3a1 1 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414");
}

:global(.r2pr1db3q) {
  fill-rule: evenodd;
  d: path("M10.293 7.707a1 1 0 0 1 0-1.414l3-3a1 1 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

:global(.s4h7atb2u) {
  fill-rule: evenodd;
  d: path("M17.707 7.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414");
}

:global(.sjskqhb8s) {
  fill-rule: evenodd;
  d: path("M14 5a1 1 0 0 1 1 1v8a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1m-4.293 7.293a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
