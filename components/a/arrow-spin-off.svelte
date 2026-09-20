<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="fwvb0bbrp"/><path class="zlgf7ibdg"/><path class="nko804_7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-spin-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fwvb0bbrp) {
  d: path("M13.937 4.211a1 1 0 0 1-1.126 1.653A5 5 0 1 0 15 10a1 1 0 1 1 2 0a7 7 0 1 1-3.063-5.789");
}

:global(.nko804_7a) {
  d: path("M18.903 12.41a1 1 0 0 1-1.826.815l-1.508-3.38a1 1 0 1 1 1.826-.815zM1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.zlgf7ibdg) {
  d: path("M13.539 12.506a1 1 0 1 1-1.078-1.685l3.482-2.227a1 1 0 0 1 1.077 1.685z");
}

</style>
