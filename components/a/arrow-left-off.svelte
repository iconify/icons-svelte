<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cae1_gb3y"/><path clip-rule="evenodd" class="fyiaghbqy"/><path clip-rule="evenodd" class="nwz_4teju"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-left-off" {...props}></Icon>
<style>
:global(.cae1_gb3y) {
  fill-rule: evenodd;
  d: path("M8.974 14.768a1 1 0 0 1-1.409-.128l-3.333-4a1 1 0 1 1 1.536-1.28l3.334 4a1 1 0 0 1-.128 1.408");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fyiaghbqy) {
  fill-rule: evenodd;
  d: path("M8.974 5.232a1 1 0 0 1 .128 1.408l-3.334 4a1 1 0 1 1-1.536-1.28l3.333-4a1 1 0 0 1 1.409-.128");
}

:global(.nwz_4teju) {
  fill-rule: evenodd;
  d: path("M6 10a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
