<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrjxtxb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:compare-arrows" {...props}></Icon>
<style>
:global(.zrjxtxb3i) {
  fill: currentColor;
  d: path("m8 18.98l-.708-.713l3.095-3.094H3v-1h7.387l-3.095-3.094l.708-.713l4.308 4.307zm8-5.365l-4.308-4.307L16 5l.708.714l-3.094 3.094H21v1h-7.386l3.094 3.094z");
}

</style>
