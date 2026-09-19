<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgl-6lbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-adf-scanner" {...props}></Icon>
<style>
:global(.hgl-6lbwn) {
  fill: currentColor;
  d: path("M19 12h-1V6c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v6H5c-1.66 0-3 1.34-3 3v3c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2v-3c0-1.66-1.34-3-3-3m-3 0H8V6h8zm2 5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
