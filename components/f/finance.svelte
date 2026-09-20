<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_lxmcbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:finance" {...props}></Icon>
<style>
:global(.r_lxmcbhh) {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V3h2v16h16v2zm1-3V9h4v9zm5 0V4h4v14zm5 0v-5h4v5z");
}

</style>
