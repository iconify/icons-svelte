<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8750-_fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:maximize-rounded" {...props}></Icon>
<style>
:global(.o8750-_fk) {
  fill: currentColor;
  d: path("M5 5q-.425 0-.712-.288T4 4t.288-.712T5 3h14q.425 0 .713.288T20 4t-.288.713T19 5z");
}

</style>
