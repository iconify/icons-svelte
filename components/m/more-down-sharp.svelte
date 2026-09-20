<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9w6w3bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:more-down-sharp" {...props}></Icon>
<style>
:global(.j9w6w3bqk) {
  fill: currentColor;
  d: path("M5.5 18.5V9h1v8.5H15v1zm5-5V4h1v8.5H20v1z");
}

</style>
