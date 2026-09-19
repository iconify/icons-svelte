<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v4pmfntfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:microsoft-alt" {...props}></Icon>
<style>
:global(.v4pmfntfv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.5 5.5h17v17h-17zm0 20h17v17h-17zm-20-20h17v17h-17zm0 20h17v17h-17z");
}

</style>
