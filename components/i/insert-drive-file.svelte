<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhg6pfbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:insert-drive-file" {...props}></Icon>
<style>
:global(.vhg6pfbud) {
  fill: currentColor;
  d: path("M6 2c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm7 7V3.5L18.5 9z");
}

</style>
