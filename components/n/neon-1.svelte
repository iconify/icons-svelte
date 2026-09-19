<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dda5k-bsr"/><path class="uwq-lsb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:neon-1" {...props}></Icon>
<style>
:global(.dda5k-bsr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 5.5h-33a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2");
}

:global(.uwq-lsb9d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 24.543l-6.973-6.994c-4.348-4.36-12.23-5.473-17.978.656c-5.645 6.019-5.054 13.475-.48 18.23l5.833 6.065");
}

</style>
