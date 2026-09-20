<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni5bwzskk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:pan-zoom" {...props}></Icon>
<style>
:global(.ni5bwzskk) {
  fill: currentColor;
  d: path("M4 20v-5h1v3.292l3.6-3.6l.708.708l-3.6 3.6H9v1zM15.4 9.308l-.708-.708l3.6-3.6H15V4h5v5h-1V5.708z");
}

</style>
