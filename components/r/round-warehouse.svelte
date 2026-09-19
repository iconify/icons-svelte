<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-339b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-warehouse" {...props}></Icon>
<style>
:global(.bi-339b3c) {
  fill: currentColor;
  d: path("M22 19V8.35c0-.82-.5-1.55-1.26-1.86l-8-3.2c-.48-.19-1.01-.19-1.49 0l-8 3.2C2.5 6.8 2 7.54 2 8.35V19c0 1.1.9 2 2 2h3v-9h10v9h3c1.1 0 2-.9 2-2m-11 0H9v2h2zm2-3h-2v2h2zm2 3h-2v2h2z");
}

</style>
