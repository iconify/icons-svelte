<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g3hbu700x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alltrails" {...props}></Icon>
<style>
:global(.g3hbu700x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.82 30.535l-8.136-11.784l-3.989 2.336l-5.905-9.79L4.5 35.784c18.136-12.337 27.782-3.774 39 .919");
}

</style>
