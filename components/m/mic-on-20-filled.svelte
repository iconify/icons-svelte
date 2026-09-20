<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="iaol434eq"/><path class="outg4qbud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:mic-on-20-filled" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iaol434eq) {
  d: path("M5.5 10a.5.5 0 0 0-1 0a5.5 5.5 0 0 0 5 5.478V17.5a.5.5 0 0 0 1 0v-2.022a5.5 5.5 0 0 0 5-5.478a.5.5 0 0 0-1 0a4.5 4.5 0 1 1-9 0z");
  fill: currentColor;
}

:global(.outg4qbud) {
  d: path("M13 10a3 3 0 0 1-6 0V5a3 3 0 0 1 6 0v5z");
  fill: currentColor;
}

</style>
