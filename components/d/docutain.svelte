<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k5c75tbtv"/><path class="eknxzzp4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:docutain" {...props}></Icon>
<style>
:global(.eknxzzp4z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.57 4.5v10.489H11.081z");
}

:global(.k5c75tbtv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.57 4.5h2.286A17.06 17.06 0 0 1 40.92 21.563v4.875A17.06 17.06 0 0 1 23.856 43.5H11.081V14.989");
}

</style>
