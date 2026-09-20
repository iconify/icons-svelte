<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xefaboy3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-upward-alt" {...props}></Icon>
<style>
:global(.xefaboy3l) {
  fill: currentColor;
  d: path("M11.5 17.308V7.416l-4.1 4.1l-.708-.708L12 5.5l5.308 5.308l-.708.708l-4.1-4.1v9.892z");
}

</style>
