<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koymt7bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-21-9-outline-sharp" {...props}></Icon>
<style>
:global(.koymt7bfv) {
  fill: currentColor;
  d: path("M3 16V8h18v8zm1-1h16V9H4zm0 0V9z");
}

</style>
