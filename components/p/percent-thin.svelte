<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y-t2a0wme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:percent-thin" {...props}></Icon>
<style>
:global(.y-t2a0wme) {
  fill: currentColor;
  d: path("m202.83 58.81l-144 144a4 4 0 0 1-5.66-5.66l144-144a4 4 0 1 1 5.66 5.65ZM53.37 98.62A32 32 0 1 1 76 108a31.82 31.82 0 0 1-22.63-9.38M52 76a24 24 0 1 0 7-17a23.85 23.85 0 0 0-7 17m160 104a32 32 0 1 1-9.37-22.63A31.82 31.82 0 0 1 212 180m-8 0a24 24 0 1 0-7 17a23.9 23.9 0 0 0 7-17");
}

</style>
