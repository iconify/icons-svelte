<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="smx72ro4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:esign" {...props}></Icon>
<style>
:global(.smx72ro4f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h7.4v37H5.5zm14.8 0h22.2v7.4H20.3zm0 14.8h22.2v7.4H20.3zm0 14.8h22.2v7.4H20.3z");
}

</style>
