<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="smk8lkbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-exit-28-regular" {...props}></Icon>
<style>
:global(.smk8lkbba) {
  fill: currentColor;
  d: path("M6.75 3A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25h10.5a.75.75 0 0 0 0-1.5H6.75a2.25 2.25 0 0 1-2.25-2.25V6.75A2.25 2.25 0 0 1 6.75 4.5h10.5a.75.75 0 0 0 0-1.5zm13.53 4.97a.75.75 0 1 0-1.06 1.06l4.22 4.22H9.75a.75.75 0 0 0 0 1.5h13.69l-4.22 4.22a.75.75 0 1 0 1.06 1.06l5.5-5.5a.75.75 0 0 0 0-1.06z");
}

</style>
