<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="j6bk8wgmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:purple-circle" {...props}></Icon>
<style>
:global(.j6bk8wgmi) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--aa8ed6, #aa8ed6);
}

</style>
