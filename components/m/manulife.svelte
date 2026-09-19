<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j1g1p344s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:manulife" {...props}></Icon>
<style>
:global(.j1g1p344s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 12.9l7.4-7.4v29.6l-7.4 7.4zm14.8 0l7.4-7.4v29.6l-7.4 7.4zm14.8 0l7.4-7.4v29.6l-7.4 7.4z");
}

</style>
