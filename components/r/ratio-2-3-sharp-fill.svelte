<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9r4-y_8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ratio-2-3-sharp-fill" {...props}></Icon>
<style>
:global(.n9r4-y_8h) {
  fill: currentColor;
  d: path("M5 1L19 1C19.5523 1 20 1.4477 20 2L20 22C20 22.5523 19.5523 23 19 23L5 23C4.4477 23 4 22.5523 4 22L4 2C4 1.4477 4.4477 1 5 1Z");
}

</style>
