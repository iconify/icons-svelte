<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iqv36961e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:camaps-fx" {...props}></Icon>
<style>
:global(.iqv36961e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 32.5a3 3 0 0 0-3-3h-10c-6.627 0-12-5.373-12-12s5.373-12 12-12s12 5.373 12 12v10a3 3 0 0 0 3 3h4a6 6 0 1 1-6 6z");
}

</style>
