<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bsrzd251d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:jupiter" {...props}></Icon>
<style>
:global(.bsrzd251d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.104 4.5h7.456v39H13.44V25.789h7.37v9.807h-4.52v3.161h10.695z");
}

</style>
