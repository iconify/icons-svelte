<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b1nalob-j"/><path class="unwr21blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nebenan-de" {...props}></Icon>
<style>
:global(.b1nalob-j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5L7.556 13.722L24 21.944l16.444-8.222zv37");
}

:global(.unwr21blo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.444 13.722v20.556l-4.11 2.055v-8.222l-8.223 4.111v8.222L24 42.5l-4.111-2.056v-8.222l-8.222-4.11v8.221l-4.111-2.055V13.722");
}

</style>
