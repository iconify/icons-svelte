<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="i4hxffrur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-brightness-1" {...props}></Icon>
<style>
:global(.i4hxffrur) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  fill: currentColor;
}

</style>
