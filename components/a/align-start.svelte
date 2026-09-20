<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbtakkbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-start" {...props}></Icon>
<style>
:global(.lbtakkbof) {
  fill: currentColor;
  d: path("M3 4V3h18v1zm4.5 5.5v-2h9v2zm0 6v-2h9v2z");
}

</style>
