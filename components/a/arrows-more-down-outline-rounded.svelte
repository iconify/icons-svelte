<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoo95jypu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrows-more-down-outline-rounded" {...props}></Icon>
<style>
:global(.qoo95jypu) {
  fill: currentColor;
  d: path("M6.808 20q-.343 0-.576-.232T6 19.192V10.5q0-.213.144-.356T6.501 10t.356.144T7 10.5V19h8.5q.213 0 .356.144t.144.357t-.144.356T15.5 20zm4-4q-.343 0-.576-.232T10 15.192V6.5q0-.213.144-.356T10.501 6t.356.144T11 6.5V15h8.5q.213 0 .356.144t.144.357t-.144.356T19.5 16z");
}

</style>
