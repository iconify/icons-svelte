<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmxz-cb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:brick-sharp" {...props}></Icon>
<style>
:global(.rmxz-cb0x) {
  fill: currentColor;
  d: path("M2 20V8h3V4h6v4h2V4h6v4h3v12z");
}

</style>
