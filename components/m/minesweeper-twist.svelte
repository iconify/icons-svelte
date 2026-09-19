<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yc5jp-bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:minesweeper-twist" {...props}></Icon>
<style>
:global(.yc5jp-bmg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.236 4.438v38.976m5.864.024H23.822m3.504-25.643l-7.774-3.219l-7.774-3.218l7.776-3.33L27.33 4.7l-.002 6.548z");
}

</style>
