<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b3cnj-b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:epik" {...props}></Icon>
<style>
:global(.b3cnj-b5i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.485 24h7.307M14.25 4.5h19.5m0 39h-19.5m0-39v39");
}

</style>
