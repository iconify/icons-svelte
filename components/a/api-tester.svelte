<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="djdzjcbar"/><path class="tij_04bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:api-tester" {...props}></Icon>
<style>
:global(.djdzjcbar) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-5 13.362v10.276");
}

:global(.tij_04bmt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.972 29.138V18.862h3.364c1.902 0 3.444 1.545 3.444 3.451s-1.542 3.451-3.444 3.451h-3.364m-3.792-.03h-4.553M14.5 29.138l3.404-10.276l3.404 10.276");
}

</style>
