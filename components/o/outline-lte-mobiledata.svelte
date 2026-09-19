<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsu1xmbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-lte-mobiledata" {...props}></Icon>
<style>
:global(.qsu1xmbgs) {
  fill: currentColor;
  d: path("M6 14h3v2H4V8h2zm3-4h2v6h2v-6h2V8H9zm12 0V8h-5v8h5v-2h-3v-1h3v-2h-3v-1z");
}

</style>
