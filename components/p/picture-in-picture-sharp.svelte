<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ald56hylg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-sharp" {...props}></Icon>
<style>
:global(.ald56hylg) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm8.308-6.308H19V7h-7.692z");
}

</style>
