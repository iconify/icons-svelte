<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggxiwpbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-phone-android" {...props}></Icon>
<style>
:global(.ggxiwpbqh) {
  fill: currentColor;
  d: path("M16 1H8C6.34 1 5 2.34 5 4v16c0 1.66 1.34 3 3 3h8c1.66 0 3-1.34 3-3V4c0-1.66-1.34-3-3-3m-2.5 20h-3c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h3c.28 0 .5.22.5.5s-.22.5-.5.5m3.5-3H7V4h10z");
}

</style>
