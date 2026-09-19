<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kadpm5bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:remove" {...props}></Icon>
<style>
:global(.kadpm5bkp) {
  fill: currentColor;
  d: path("M19 13H5v-2h14z");
}

</style>
