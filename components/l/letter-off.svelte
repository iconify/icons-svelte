<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y75d9fjof"/><path clip-rule="evenodd" class="aryxucb_t"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:letter-off" {...props}></Icon>
<style>
:global(.aryxucb_t) {
  fill-rule: evenodd;
  d: path("m17.648 5.261l-7.045 6a1 1 0 0 1-1.301-.004l-6.955-6C1.645 4.652 2.073 3.5 3 3.5h14c.93 0 1.356 1.158.648 1.761M5.69 5.5l4.27 3.683L14.282 5.5z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.y75d9fjof) {
  fill-rule: evenodd;
  d: path("M17 3.5H3a1 1 0 0 0-1 1v11a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-11a1 1 0 0 0-1-1m-13 11v-9h12v9z");
}

</style>
