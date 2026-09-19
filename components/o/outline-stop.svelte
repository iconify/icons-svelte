<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbl3q_hii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-stop" {...props}></Icon>
<style>
:global(.sbl3q_hii) {
  fill: currentColor;
  d: path("M16 8v8H8V8zm2-2H6v12h12z");
}

</style>
