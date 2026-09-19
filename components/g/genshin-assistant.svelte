<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mei_uh1ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:genshin-assistant" {...props}></Icon>
<style>
:global(.mei_uh1ba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l6.634 13.252L44.5 24l-13.866 7.248L24 44.5l-6.634-13.252L3.5 24l13.866-7.248zM3.5 24h41M24 3.5v41m-6.634-13.252l13.268-14.496m0 14.496L17.366 16.752");
}

</style>
