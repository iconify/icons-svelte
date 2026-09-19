<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ntz-uxbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hikar" {...props}></Icon>
<style>
:global(.ntz-uxbhu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.657 10.5v-6h-6.5v6m0 13v20h6.5v-20M35 10.5H6v13h29l7-6.5z");
}

</style>
