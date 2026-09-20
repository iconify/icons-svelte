<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gnxr7zbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:exclude-square-fill" {...props}></Icon>
<style>
:global(.gnxr7zbld) {
  fill: currentColor;
  d: path("M88 88v80H40a8 8 0 0 1-8-8V40a8 8 0 0 1 8-8h120a8 8 0 0 1 8 8v48Zm128 0h-48v80H88v48a8 8 0 0 0 8 8h120a8 8 0 0 0 8-8V96a8 8 0 0 0-8-8");
}

</style>
