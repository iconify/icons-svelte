<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2ftrtbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:finance-outline-sharp" {...props}></Icon>
<style>
:global(.k2ftrtbih) {
  fill: currentColor;
  d: path("M3.5 20V3h1v16h16v1zm3.885-3.5V9.192h2V16.5zm4.5 0V4.192h2V16.5zm4.5 0v-3.308h2V16.5z");
}

</style>
