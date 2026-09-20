<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvdfbmipk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:left-panel-open-outline-sharp" {...props}></Icon>
<style>
:global(.zvdfbmipk) {
  fill: currentColor;
  d: path("M12.5 8v8l4-4zM5 19h3V5H5zm5 0h9V5h-9zm-2 0H5zm-5 2V3h18v18z");
}

</style>
