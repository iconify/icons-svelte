<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhw7zbbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-text-fill-sharp" {...props}></Icon>
<style>
:global(.rhw7zbbtv) {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3ZM5 20h14V10H5Zm3-8h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
