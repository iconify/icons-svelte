<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="rno7hacaa"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:circle-big-filled-circle" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kphejjb8s) {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

:global(.rno7hacaa) {
  d: path("M22.5 13a9.5 9.5 0 1 1-19 0a9.5 9.5 0 0 1 19 0");
}

</style>
