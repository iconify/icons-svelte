<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hvzpk2bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:norsk-tipping" {...props}></Icon>
<style>
:global(.hvzpk2bat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.783 6.396L23.47 24.242L5.5 42.5m24.082-23.582L42.5 5.5M28.836 29.894l13.499 12.319");
}

</style>
