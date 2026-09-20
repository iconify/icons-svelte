<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbbfu-92e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hov" {...props}></Icon>
<style>
:global(.qbbfu-92e) {
  fill: currentColor;
  d: path("M12 22L6 12l6-10l6 10z");
}

</style>
