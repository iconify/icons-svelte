<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><circle class="z6kz0pbfd"/><path class="c-3-ql74i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:etherpad" {...props}></Icon>
<style>
:global(.c-3-ql74i) {
  fill: none;
  stroke: currentColor;
  d: path("M14.5 5.5v37m19-37v37");
}

:global(.ll0g54h-q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

:global(.z6kz0pbfd) {
  cx: 24px;
  cy: 24px;
  r: 13.9px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 7;
}

</style>
