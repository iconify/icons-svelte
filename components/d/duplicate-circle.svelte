<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xitur4brx"/><path class="en_3l1iub"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:duplicate-circle" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.en_3l1iub) {
  d: path("M9.5 16.5h-2a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v2h-2v-1h-6v6h1z");
}

:global(.kphejjb8s) {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

:global(.xitur4brx) {
  fill-rule: evenodd;
  d: path("M18.5 9.5h-8a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-8a1 1 0 0 0-1-1m-7 8v-6h6v6z");
}

</style>
