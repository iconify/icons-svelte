<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="l97nb-quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-wifi-1-bar" {...props}></Icon>
<style>
:global(.l97nb-quh) {
  cx: 12px;
  cy: 18px;
  r: 2px;
  fill: currentColor;
}

</style>
