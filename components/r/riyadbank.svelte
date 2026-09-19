<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yun3zdbqw"/><path class="xqcs4gbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:riyadbank" {...props}></Icon>
<style>
:global(.xqcs4gbrs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 17.833V5.5H42.5");
}

:global(.yun3zdbqw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 30.167H42.5V5.5L30.167 17.833V42.5H5.5V17.833h12.333v12.333L5.5 42.499");
}

</style>
