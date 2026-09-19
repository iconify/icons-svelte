<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g7_jsob2k"/><path class="ut2ivibbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:arccreate" {...props}></Icon>
<style>
:global(.g7_jsob2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.31 29.375v-10.75L24 13.25l-9.31 5.375v10.75L24 34.75zl9.31 5.375L24 45.5L5.38 34.75v-21.5L24 2.5l18.62 10.75l-9.31 5.375");
}

:global(.ut2ivibbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.69 40.125V7.875l-4.655 2.688v26.874");
}

</style>
