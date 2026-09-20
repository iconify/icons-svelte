<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xte972wur"/><path class="p1nc4nb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:person" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.p1nc4nb1r) {
  d: path("M17 18a1 1 0 1 1-2 0v-2.5c0-2.494-2.206-4.5-4.984-4.5C7.23 11 5 13.013 5 15.5l.002 2.5a1 1 0 1 1-2 0L3 15.5C3 11.86 6.169 9 10.016 9C13.86 9 17 11.857 17 15.5z");
}

:global(.xte972wur) {
  fill-rule: evenodd;
  d: path("M6 6a4 4 0 1 0 8 0a4 4 0 0 0-8 0m6 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
