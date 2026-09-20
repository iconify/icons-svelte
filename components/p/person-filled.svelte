<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ss13veb9o"/><path clip-rule="evenodd" class="w6ei_8b5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:person-filled" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ss13veb9o) {
  d: path("M10 9a3 3 0 1 0 0-6a3 3 0 0 0 0 6Z");
}

:global(.w6ei_8b5u) {
  fill-rule: evenodd;
  d: path("M16 15.5c0-3.191-2.686-5.5-6-5.5s-6 2.309-6 5.5l.002 1.5a1 1 0 0 0 1 1H15a1 1 0 0 0 1-1v-1.5Z");
}

</style>
