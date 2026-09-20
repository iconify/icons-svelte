<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7wixs2-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:device-band-outline-sharp" {...props}></Icon>
<style>
:global(.q7wixs2-u) {
  fill: currentColor;
  d: path("M8.866 21V8.73h-.693V6.77h.693V3h6.25v3.77h.692v1.96h-.692V21zm1-12.75V20h4.25V8.25zm0-1h4.25V4h-4.25zm0 1h4.25zm0-1h4.25z");
}

</style>
