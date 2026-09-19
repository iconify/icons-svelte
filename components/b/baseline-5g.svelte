<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1todncnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-5g" {...props}></Icon>
<style>
:global(.o1todncnw) {
  fill: currentColor;
  d: path("M17 13h2v2h-5V9h7c0-1.1-.9-2-2-2h-5c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h5c1.1 0 2-.9 2-2v-4h-4zM3 13h5v2H3v2h5c1.1 0 2-.9 2-2v-2c0-1.1-.9-2-2-2H5V9h5V7H3z");
}

</style>
