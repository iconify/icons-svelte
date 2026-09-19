<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="rnr15yq7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-fiber-manual-record" {...props}></Icon>
<style>
:global(.rnr15yq7m) {
  cx: 12px;
  cy: 12px;
  r: 8px;
  fill: currentColor;
}

</style>
